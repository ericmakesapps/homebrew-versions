# Eric makes apps — Homebrew Versions Tap

This is a public homebrew tap available with some older version of formulas. If you want to add one, feel free to create a pull request!

## Using the versions here

If you need one of the versions already included here, then awesome! That's easy. Just tap this tap with `brew tap ericmakesapps/versions` then install the version you need, e.g., `brew install weasyprint@59.0`.

## Tapping a version for yourself

If you want to add a new version here, feel free. You'll want to use `brew extract`. You may have to tap `homebrew/core` explicitly to extract (I had to). That would be with `brew tap homebrew/core`. After that, you can extract the version you want with `brew extract --version=59.0 weasyprint ericmakesapps/versions`. After it creates that version, go to the directory of the tap on your local system, fork this repository, add it to the origins of the git settings in that directory, push it up, then create a pull request!
