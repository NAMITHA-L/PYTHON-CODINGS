def countPairs(arr, target):
    freq = {}
    cnt = 0

    for i in range(len(arr)):
        
        if (target - arr[i]) in freq:
            cnt += freq[target - arr[i]] 
        
        freq[arr[i]] = freq.get(arr[i], 0) + 1 
    return cnt
