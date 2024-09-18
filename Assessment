def find_max_skill(N, M, A, B):
    opponents = [(A[i], B[i]) for i in range(N)]
    opponents.sort()
    skill = M  
    for a, b in opponents:
        if skill >= a:  
            skill += b  
        else:
            break  
    return skill

# Example 1
N1, M1 = 4, 2
A1 = [8, 9, 3, 2]
B1 = [5, 4, 1, 3]

# Example 1
N2, M2 = 5, 3
A2 = [8, 4, 5, 6, 7]
B2 = [9, 8, 7, 5, 6]

# Example 1
N3, M3 = 5, 9
A3 = [2, 3, 6, 7, 8]
B3 = [3, 4, 2, 2, 3]

# Resule
output1 = find_max_skill(N1, M1, A1, B1)
output2 = find_max_skill(N2, M2, A2, B2)
output3 = find_max_skill(N3, M3, A3, B3)
