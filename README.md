# Search-Insert-Position
#Given a sorted array and a target value, return the index if the target is found. If not, return the index where it would be if it were inserted in order.
class Solution {
     public int searchInsert(int[] nums, int target) {
   int i=0;

    while(i<nums.length){
      if (nums[i] == target || nums[i] > target){
        return i;
      }
    else{
        i++;
        }
    }

    return i;

}
}
