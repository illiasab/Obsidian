## PrefixSum -> Prefix Sum is the sum of the first i consecutive elements. Here is the formula and code template: prefixSum[i] = A[0]+A[1]+…+A[i-1]

## More deep understanding of prefixSum is that when you have main array and the array where you will count prefixsum you gonna have your PrefixSum array be counted n + 1 time with 0 and then replaced with prefixSums

### Most Common implementation of prefixSum

func TotalOfPrefix(nums: Int)  -> int {
	var prefixSum = Array(repeating: 0, count: n + 1)
	for i in 1..<n {
		prefixSum = prefixSum[i - 1] + nums[i]
		total = String(prefixSum[i])
		// print the value 
	}
}

