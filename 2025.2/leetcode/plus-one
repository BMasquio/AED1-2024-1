class Solution:
    def plusOne(self, digits: List[int]) -> List[int]:
        i=len(digits)-1
        v1 = 1
        while(i >= 0 and v1 == 1):
            if (digits[i] == 9):
                digits[i] = 0
                v1 = 1
            else:
                digits[i] = digits[i] + 1
                v1 = 0
            i = i - 1
        if(v1 == 1):
            digits = [1]+digits
        return digits
