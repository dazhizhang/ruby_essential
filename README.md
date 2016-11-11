# rubyonrails_essential


##################################################

Array

[]
["Matz!", "Matz!", "Matz!"]

##################################################

Hashes

empty_hash = Hash.new
=> {}

my_hash = Hash.new("The Default")
my_hash["random_key"]
=> "The Default"

my_hash = {
  "key1" => value1,
  :key2  => value2,
  3 => value 3
}

my_hash = {
  :a => "Artur",
  :l => "Linda",
  :r => "Ryan",
  :z => "Zach"
}
=> {:a => "Artur", :l => "Linda", :r => "Ryan", :z => "Zach"}

SHORTHAND HASHES
my_hash = {
  name: "Artur",
  age:  21
}
=> { :name => "Artur", :age => 21 }

##################################################

Blocks

一行模式 
[1,2,3,4].each { |number| puts number }

多行模式
[1,2,3,4].each do |number|
  puts "You know what number I love?"
  puts "I love #{number}!"
end

##################################################

还有一个ruby特有的literal，字面量

##################################################

动态语言特性 blcok，proc，lambda，yield
http://rubyer.me/blog/917/

网站：

http://ruby-doc.org/

http://rspec.info/

http://tryruby.org/

http://www.tutorialspoint.com/ruby/

http://www.saasbook.info/students

http://guides.ruby-china.org/
