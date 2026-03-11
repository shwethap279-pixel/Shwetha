A = [[1, 2, 3],
     [4, 5, 6],
     [7, 8, 9]]

B = [[9, 8, 7],
     [6, 5, 4],
     [3, 2, 1]]

# Matrix Addition
def add_matrices(X, Y):
    result = []
    for i in range(len(X)):
        row = []
        for j in range(len(X[0])):
            row.append(X[i][j] + Y[i][j])
        result.append(row)
    return result

# Matrix Multiplication
def multiply_matrices(X, Y):
    result = []
    for i in range(len(X)):
        row = []
        for j in range(len(Y[0])):
            sum_val = 0
            for k in range(len(Y)):
                sum_val += X[i][k] * Y[k][j]
            row.append(sum_val)
        result.append(row)
    return result

# Perform operations
print("Matrix A:")
for row in A:
    print(row)

print("\nMatrix B:")
for row in B:
    print(row)

print("\nAddition of A and B:")
for row in add_matrices(A, B):
    print(row)

print("\nMultiplication of A and B:")
for row in multiply_matrices(A, B):
    print(row)
