# rubyonrails_essential

两种方法处理block
一行模式 
[1,2,3,4].each { |number| puts number }

多行模式
[1,2,3,4].each do |number|
  puts "You know what number I love?"
  puts "I love #{number}!"
end
