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

### Concatenating Strings (3 ways to do it)
> 'Ruby' + 'Monk'  
> "Ruby".concat("Monk")  
> "Ruby" << "Monk"  

### Replacing substring (first occurence only)
> "I should look into your problem when I get time".sub('I','We')  
> output: **We should look into your problem when I get time**

### Replacing substring (all occurences )
> "I should look into your problem when I get time".gsub('I','We')

### Replace all vowels in string with the number 1 (REGEX)
> 'RubyMonk'.gsub(/[aeiou]/,'1')  
> output: **R1byM1nk**


### Replace all capital letters in string with the number 0 (REGEX)
> 'RubyMonk Is Pretty Brilliant'.gsub(/[RMIPB]/, '0')  
> output: **0uby0onk 0s 0retty 0rilliant**

### Finding chars in a string (REGEX) (used when you don't know what you're looking for)
> 'RubyMonk Is Pretty Brilliant'.match(/ ./)  
> output:  **I**

### Boolean expressions
> name == "Bob"  

#### Is age less than or equal to 35 ?
> age <= 35  

#### Is age greater than or equal to 23 and name is 'Bob' OR 'Jill' ?
> age >= 23 && (name == 'Bob' || name == 'Jill')

#### Name is not Bob
> ! (name == 'Bob')  

### IF / ELSE
> def check_sign(number)  
   if number > 0  
     "#{number} is positive"  
   else  
     "#{number} is negative"  
   end          
end
