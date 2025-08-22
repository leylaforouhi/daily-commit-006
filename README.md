def fibonacci(n):
    sequence = [0, 1]
    for i in range(2, n):
        sequence.append(sequence[-1] + sequence[-2])
    return sequence

if __name__ == "__main__":
    print(f"First 10 Fibonacci numbers: {fibonacci(10)}")
