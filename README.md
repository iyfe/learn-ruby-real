# IyfePalindrome
`iyfe_palindrome` is a sample Ruby gem created in Learn enough Ruby to be dangerous

## Installation

To install `iyfe_palindrome`, add this line to your application's `Gemfile`:

```ruby
gem 'iyfe_palindrome'
```

And then execute:

    $ bundle install

Or install it yourself as:

    $ gem install iyfe_palindrome

## Usage
`iyfe_palindrome` adds a `palindrome?` method to the `String` class, and can be used as follows:

```
$ irb
>> require 'mhartl_palindrome'
>> "honey badger".palindrome?
=> false
>> "deified".palindrome?
=> true
>> "Able was I, ere I saw Elba.".palindrome?
=> true
>> phrase = "Madam, I'm Adam."
>> phrase.palindrome?
=> true
```
