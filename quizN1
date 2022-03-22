# 1

# class Mylist(object):  # თუმცა მხოლოდ Mylist:-იც შეიძლება, რადგა default-ად იგულისხმება object.
#     def __init__(self, data):
#         self.data = data

#     def __add__(self, other):
#         return self.data + other.data
 
#     def __mul__(self, other):
#         return self.data * other
 
#     def __str__(self):
#         return f'{self.data}'
 
 
# obj1 = Mylist([1, 2, 3])
# obj2 = Mylist([5, 6])
# print(obj1 * 2)
# print(obj1 + obj2)
# print(obj1)   # გივეა რაც print(str(obj1))



# 2
 
# class Testpaper:
#     def __init__(self, subject, mark_scheme, pass_mark):
#         self.subject = subject
#         self.mark_scheme = mark_scheme
#         self.pass_mark = pass_mark
 
# class Student:
#     def __init__(self):
#         self.tests_taken = 'No tests taken'
 
#     def take_test(self, test_paper, answers):
#         number = 0
#         for i in range(len(answers)):
#             if test_paper.mark_scheme[i] == answers[i]:
#                 number += 1

#         n = round(len(answers) * float(test_paper.pass_mark[:-1]) / 100)
#         if self.tests_taken == 'No tests taken':
#             self.tests_taken = {}
 
#         if number >= n:
#             self.tests_taken[test_paper.subject] = f'passed! ({round((number/len(answers))*100)}%)'
#         else:
#             self.tests_taken[test_paper.subject] = f'Failed! ({round((number / len(answers)) * 100)}%)'
 
 
# # მაგალითის მიხედვით შემოტანილი ობიექტები:
# paper1 = Testpaper('Maths', [1, 2, 3], '60%')
# paper2 = Testpaper('Chemistry', [4, 5, 6], '75%')
 
# student1 = Student()
# student2 = Student()
 
# student1.tests_taken
# student1.take_test(paper1, [8, 7, 3])
# print(student1.tests_taken)
 
# student2.take_test(paper2, [1, 2, 3])
# print(student2.tests_taken)


# # ჩემი შემოტანილი ობიექტები:
# t1 = Testpaper('math', [2, 5, 6], '25%')
# t2 = Testpaper('biology', [1, 6, 9], '45%')
# s1 = Student()
# s2 = Student()
# print(s1.tests_taken)
# print(s2.tests_taken)
# s1.take_test(t1, [2, 5, 3])
# s2.take_test(t2, [6, 7, 9])
# print(s1.tests_taken)
# print(s2.tests_taken)
