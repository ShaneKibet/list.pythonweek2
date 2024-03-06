
def rate_performance(marks):
    if marks >= 80:
        return "Distinction"
    elif 60 <= marks < 80:
        return "Credit"
    elif 40 <= marks < 60:
        return "Fair"
    elif marks < 40:
        return "Fail"
    else:
        return "Invalid marks"

# Test the function with different marks
marks_list = [95, 75, 55, 35, 25]
for marks in marks_list:
 print(f"Marks: {marks}, Rating: {rate_performance(marks)}")
