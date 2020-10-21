# Hackerrank_solutions
Practice>PythonBasic>Data Types>Finding the percentage

if __name__ == '__main__':
    n = int(raw_input())
    student_marks = {}
    for _ in range(n):
        line = raw_input().split()
        name, scores = line[0], line[1:]
        scores = map(float, scores)
        student_marks[name] = scores
    query_name = raw_input()
    k = student_marks[query_name]
    add = sum(k)
    leng = len(k)
    print("%.2f" %(add/leng))
    
