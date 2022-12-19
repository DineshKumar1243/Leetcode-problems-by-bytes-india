class Solution {
    public int longestConsecutive(int[] nums) {
        HashSet<Integer> set=new HashSet<>();
        int max=0;
        for(int x:nums)
            set.add(x);
        for(int i=0;i<nums.length;i++){
            int c=1;
            if(!set.contains(nums[i]-1)){
               int c1=nums[i]+1;
               while(set.contains(c1)){
                    c++;c1++;
                }       
            }
            max=Integer.max(max,c);
          
        }return max;
    }
}
