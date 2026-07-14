# String-Assignment

#Q1 — Professional Email Management System

employee_email = "muhammad.ahmed2026@softwarehouse.com"

user_name = employee_email[0:14]
company_name = employee_email[19:32]
domain_name =  employee_email[-4:]

print("user name:" , user_name)
print("company name:" , company_name)
print("domain name:" , domain_name)
print("frist 12 charaters:" , employee_email[0:13])
print("last 10 charaters:" , employee_email[-11:])

# Q2 — E-Commerce Product Code Analyzer

product_code = "MOB-APPLE-IPHONE15PRO-256GB-BLACK"

product_category = product_code[0:3]
company_name = product_code[4:9]
model_name = product_code[10:21]
storage_size = product_code[22:27]
product_color = product_code[28:]

print("product category:" , product_category) 
print("companyname:" , company_name) 
print("model name:" , model_name) 
print("storage size:" , storage_size) 
print("product color:" , product_color) 
print("first char of company:", company_name[0]) 
print("last char of model:",    model_name[-1]) 

# Q3 — Online Banking SMS Processor

banking_SMS = "PKR 25000 has been successfully transferred to account 45892"

transferred_amount = banking_SMS[4:9]
account_number = banking_SMS[55:]
transaction_status_word = banking_SMS[19:31]
first_25_characters = banking_SMS[0:26]
last_15_characters = banking_SMS[-15:]
Count_letter_a = banking_SMS

print("transferred amount:" , transferred_amount) 
print("account number:" , account_number) 
print("transaction status word:" , transaction_status_word) 
print("first_25_characters:" , banking_SMS[0:26]) 
print("last 15 characters:" , banking_SMS[-15:])
print("letter a count:", banking_SMS.count("a"))

# Q4 — University Student Record Formatter

student_record = "BSCS|2026|045|Muhammad Ali Khan"

department_name = student_record[0:4]
batch_year = student_record[5:9]
roll_number = student_record[10:13]
full_name = student_record[14:]
first_name = student_record[14:22]
initials = full_name[0] + "." + full_name[9] + "." + full_name[13] + "."

print("Department Name:", department_name)
print("Batch Year:", batch_year)
print("Roll Number:", roll_number)
print("Student Full Name:", full_name)
print("First Name:", first_name)
print("Initials:", initials)

# Q5 — Website URL Processing System

url = "https://www.amazonshoppingstore.com"

remove_https = url[8:]
remove_www = url[12:]
website_name = url[12:-4]
domain_extension = url[-4:]
ends_with_com = url.endswith(".com")
middle_portion = url[10:25]

print("remove https://:" , remove_https)
print("remove www.:" ,  remove_www)
print("Website Name:" , website_name)
print("Domain Extension:" , domain_extension)
print("Ends with .com:" ,  ends_with_com)
print("Middle Portion:" ,  middle_portion)

# Q6 — Secure Password Formatter

password = "MySecure@Pass123"

hidden_format = password[0] + "*" * (len(password) - 2) + password[-1]
first_character = password[0]
last_character = password[-1]
total_length = len(password)
middle_characters = password[4:12]
ends_with_number = password[-1].isdigit()

print("Hidden Format:" , hidden_format)
print("First Character:" , first_character)
print("Last Character:" , last_character)
print("Total Length:" , total_length)
print("Middle Characters:" , middle_characters)
print("Ends with Number:" , ends_with_number)

# Q7 - File Management System

filename = "python_final_project_documentation_2026.pdf"

without_underscores = filename.replace("_", " ")
without_extension = filename[:-4]
extension_only = filename[-4:]
is_pdf = filename.endswith(".pdf")
first_20_characters = filename[:20]
last_10_characters = filename[-10:]

print("Without Underscores:" , without_underscores)
print("Without Extension:" , without_extension)
print("Extension Only:" , extension_only)
print("Is PDF:" , is_pdf)
print("First 20 Characters:" , first_20_characters)
print("Last 10 Characters:" , last_10_characters)

# Q8 - Social Media Username Generator

first_name = "mariya"
last_name = "sharif"
favorite_game = "GTA 5"
lucky_number = "44"

username = first_name + "_" + last_name + "_" + favorite_game + "_" + lucky_number

without_lucky_number = username[:-3]
game_name = username[14:19]
only_lucky_number = username[-2:]
first_8_characters = username[:9]
last_6_characters = username[-6:]
capitalize_format = username.capitalize()

print("Username:" , username)
print("Without Lucky Number:" , without_lucky_number)
print("Game Name:" , game_name)
print("Only Lucky Number:" , only_lucky_number)
print("First 8 Characters:" , first_8_characters)
print("Last 6 Characters:" , last_6_characters)
print("Capitalize Format:" , capitalize_format)

# # Q9 - Chat Application Message Analyzer

message = "hello sir i have completed my python assignment successfully"

capitalized = message.capitalize()
replaced = message.replace("python", "javascript")
position = message.find("assignment")
count_s = message.count("s")
first_18 = message[:19]
last_20 = message[-20:]
word_completed = message[17:26]

print("Capitalized:" , capitalized)
print("Replaced:" , replaced)
print("Position:" , position)
print("Count of 's':" , count_s)
print("First 18 Chars:" , first_18)
print("Last 20 Chars:" , last_20)
print("Word Completed:" , word_completed)

# Q10 - Online Course Information System

course = "Python Programming Complete Bootcamp 2026"

course_name = course[:-5]
batch_year = course[-4:]
first_word = course[:6]
last_word = course[37:]
first_15 = course[:16]
last_12 = course[-12:]
count_o = course.count("o")
ends_with_2026 = course.endswith("2026")

print("Course Name:" , course_name)
print("Batch Year:" , batch_year)
print("First Word:" , first_word)
print("Last Word:" , last_word)
print("First 15 Chars:" , first_15)
print("Last 12 Chars:" , last_12)
print("Count of 'o':" , count_o)
print("Ends with 2026:" , ends_with_2026)


