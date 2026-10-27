# student-grade-analysis
Python project for analyzing student grades
# قائمة أسماء الطلاب
student_list = ["Ahmed", "Mona", "Sara", "Ali"]

# قائمة درجات الطلاب المقابلة
scores = [85, 42, 90, 48]

print("--- تقرير تحليل درجات الطلاب ---")

# حلقة تكرارية لفحص درجات كل طالب وتصنيفها
for i in range(len(student_list)):
    name = student_list[i]
    score = scores[i]
    
    # تحديد الحالة: ناجح أم راسب
    if score >= 50:
        status = "Pass"
    else:
        status = "Fail"
        
    print(f"Student: {name} | Score: {score} | Status: {status}")