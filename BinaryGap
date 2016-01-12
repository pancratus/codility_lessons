def solution(N):
    maxLen = 0
    curLen = 0
    while (N + 1) % 2:
        N = N / 2
    while N:
        if N % 2:
            maxLen = max(maxLen, curLen)
            curLen = 0
        else:
            curLen = curLen + 1
        N = N / 2
    return maxLen
    pass
