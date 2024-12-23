## Binary Search -> Alghoritm for finding target in sorted in ascending order array.

### Common way of finding in example below

func FindSum(nums: [Int], target: Int) -> Int {
var left = 0
var right = nums.count - 1
	while left <= right {
		let mid = (right + left) / 2 // pointer for main actions 
		// etc.
	}
}

moving mid to lower bound as left and upperbound as right.



var nums = [7, 11, 13, 15,17,23]