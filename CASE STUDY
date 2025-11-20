CASE STUDY:1
Question: Design a simple student management system. Store student information 
including ID, name, age, and courses enrolled. Use appropriate data structures to 
efficiently manage this information. 
Program: 
Python 
# Using a dictionary to store student data, where keys are student IDs 
# and values are dictionaries containing name, age, and a list of courses. 
students = { 
"S001": {"name": "Alice", "age": 20, "courses": ["Math", "Physics"]}, 
"S002": {"name": "Bob", "age": 21, "courses": ["Chemistry", "Biology"]}, 
"S003": {"name": "Charlie", "age": 19, "courses": ["Math", "Computer 
Science"]} 
} 
def add_student(student_id, name, age, courses): 
"""Adds a new student to the system.""" 
students[student_id] = {"name": name, "age": age, "courses": courses} 
print(f"Student {name} added.") 
def enroll_course(student_id, course_name): 
"""Enrolls a student in a new course.""" 
    if student_id in students: 
        students[student_id]["courses"].append(course_name) 
        print(f"Student {students[student_id]['name']} enrolled in {course_name}.") 
    else: 
        print("Student not found.") 
 
def get_student_info(student_id): 
    """Retrieves and prints a student's information.""" 
    if student_id in students: 
        info = students[student_id] 
        print(f"ID: {student_id}, Name: {info['name']}, Age: {info['age']}, Courses: 
{', '.join(info['courses'])}") 
    else: 
        print("Student not found.") 
 
# Example usage 
add_student("S004", "David", 22, ["History"]) 
enroll_course("S001", "Chemistry") 
get_student_info("S001")

CASE STUDY:2
Question: Create a system to manage product inventory. Each product has a name, 
price, and quantity. Efficiently handle adding new products, updating quantities, 
and listing available products. 
Program: 
Python 
# Using a dictionary where keys are product names and values are tuples 
# containing (price, quantity). 
inventory = { 
    "Laptop": (1200, 10), 
    "Mouse": (25, 50), 
    "Keyboard": (75, 20) 
} 
 
def add_product(product_name, price, quantity): 
    """Adds a new product to the inventory.""" 
    inventory[product_name] = (price, quantity) 
    print(f"Product '{product_name}' added.") 
 
def update_quantity(product_name, new_quantity): 
    """Updates the quantity of an existing product.""" 
    if product_name in inventory: 
        price, _ = inventory[product_name] # Get current price 
        inventory[product_name] = (price, new_quantity) 
        print(f"Quantity of '{product_name}' updated to {new_quantity}.") 
    else: 
        print("Product not found.") 
 
def list_products(): 
"""Lists all products and their details.""" 
print("Current Inventory:") 
for product, details in inventory.items(): 
price, quantity = details 
print(f"- {product}: Price=${price}, Quantity={quantity}") 
# Example usage 
add_product("Monitor", 300, 15) 
update_quantity("Laptop", 8) 
list_products() 

Case Study 3: Unique User Tags 
Question: Implement a system to manage unique tags associated with users. Allow 
adding tags to users and checking if a user has a specific tag. 
Program: 
Python 
# Using a dictionary where keys are user IDs and values are sets of tags. 
user_tags = { 
"U001": {"admin", "developer", "tester"}, 
"U002": {"developer", "frontend"}, 
"U003": {"tester"} 
} 
def add_tag_to_user(user_id, tag): 
    """Adds a tag to a user's set of tags.""" 
    if user_id in user_tags: 
        user_tags[user_id].add(tag) 
        print(f"Tag '{tag}' added to user '{user_id}'.") 
    else: 
        print("User not found.") 
 
def check_user_has_tag(user_id, tag): 
    """Checks if a user has a specific tag.""" 
    if user_id in user_tags: 
        if tag in user_tags[user_id]: 
            print(f"User '{user_id}' HAS tag '{tag}'.") 
            return True 
        else: 
            print(f"User '{user_id}' DOES NOT have tag '{tag}'.") 
            return False 
    else: 
        print("User not found.") 
        return False 
 
# Example usage 
add_tag_to_user("U001", "backend") 
check_user_has_tag("U002", "developer") 
check_user_has_tag("U003", "admin")
