# TextMate Bundle for Shoulda

Version 0.3 by David Lowenfels

The syntax and preferences are based on the RSpec bundle.
The snippets were contributed by Dan Croak and Sam Livingston-Gray, and mashed up by me.
I modified the Ruby bundle’s “run focused unit test” to support the shoulda syntax.

To install with Git:

    mkdir -p ~/Library/Application\ Support/TextMate/Bundles
    cd ~/Library/Application\ Support/TextMate/Bundles
    git clone git://github.com/marcosgz/ruby-shoulda-tmbundle.git "Ruby Shoulda.tmbundle"
    osascript -e 'tell app "TextMate" to reload bundles'