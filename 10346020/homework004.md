def is_leap_year?(year)
  if year % 400 == 0
     puts "西元#{year}年是閏年"
  else
     if year % 4 == 0 && year % 100 !=0
        puts "西元#{year}年是閏年"
     else
        puts "西元#{year}年是平年"
     end
  end
end


puts is_leap_year?(1900)   #平年
puts is_leap_year?(2000)   #閏年
