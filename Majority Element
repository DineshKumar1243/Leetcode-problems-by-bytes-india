class Solution {
    public int majorityElement(int[] nums) {
          int vote=nums[0],voteCount=1;
        for(int i=1;i<nums.length;i++){
            if(nums[i]==vote) voteCount++;
            else{
                voteCount--;
                if(voteCount==0){
                    vote=nums[i];voteCount++;
                }
            }
        }return vote;
    }
}
