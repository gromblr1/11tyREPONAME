## Ruby

> variables are #{varname}  

### Searching a string
> "[Luke:] I can’t believe it. [Yoda:] That is why you fail.".include? 'Yoda'

### Searching specific char in string
> "I am a Rubyist".index 'R'

### Checking string that starts/ends with:
> "Ruby is a beautiful language".start_with? 'Ruby'  
> "I can't work with any other language but Ruby".end_with? 'Ruby'  

It is conventional in Ruby to have '?' at the end of the method if that method returns only boolean values.

### String: lowercase to uppercase etc, swap cases and split
> puts 'i am in lowercase'.upcase  
> 'This is Mixed CASE'.downcase  
> "ThiS iS A vErY ComPlEx SenTeNcE".swapcase
> 'Fear is the path to the dark side'.split
