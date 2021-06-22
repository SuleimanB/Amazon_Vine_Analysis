Purpose of Analysis

The Purpose of this analysis will be to determine if any bias exists within the Vine Program. An analysis was conducted using PySpark and the Video Games Product Review data that was made available. The overall question that should be addressed by the end of this analysis is whether or not an observable difference is present in the percentage of 5-star reviews for those in and outside of the Vine Program. 

Results 

How many Vine Reviews and Non-Vine Reviews were there? 

![image-20210621225028032](C:\Users\CC3X5\AppData\Roaming\Typora\typora-user-images\image-20210621225028032.png)

As we can see through the count_yes and count_no variables, their appears to be quite a gap between the amount of vine reviews and non-vine reviews when looking at the total count with count_yes garnering 4291 reviews compared to the almost 2 million reviews of non-vine reviewers. We will see as a result of this quite a bit of skewness to the data due to the lack of vine reviews when compared to their counterparts which will make quite a difference in the remaining questions regarding 5-star reviews and ultimately count.  

How many Vine reviews were 5-stars? How many non-Vine Reviews were 5 stars? 

![image-20210621225114528](C:\Users\CC3X5\AppData\Roaming\Typora\typora-user-images\image-20210621225114528.png)

Now here we can see the effects of having such a disparity between the two categories. Further filtering the results whittled down the Vine reviews to only 1607 reviews but did reduce the reviews for the non-vine category to roughly a million instead. As we can, the direct lack of these two figures being so far a part from one another makes a quantitative analysis between the two unwise without further tuning of the sample or study being conducted.  

What percentage of Vine reviews were 5 stars? What percentage of non-Vine Reviews were 5 stars? 

![image-20210621225127348](C:\Users\CC3X5\AppData\Roaming\Typora\typora-user-images\image-20210621225127348.png)

In total, their were only roughly 1 million 5-star reviews with the vast, overwhelming majority being not part of the vine designation and the vine review section carrying a very miniscule total amount. It is safe to say that as a result of how far apart these numbers are, it is not recommended to take this baseline information and make points about the effectiveness or performance of the vine review group compared to the non-vine group. 

Summary 

In summary as a result of the low amount of Vine Program reviews, their is a clear amount of inherent bias to the substantial difference between the number of reviews for the two categories. Further studying or examination will need to have very structured ideas and implementation of the sample in order to ensure no bias is observed. The other option would be to accumulate more reviews for this vine program and ensure an actionable sample can be used. One note would be perhaps use the Vine Program reviews to see if more helpful comments and votes were associated for these reviews when compared to non-Vine reviews to see if perhaps this Vine program has more positive interactions or desired interactions with Amazon products and services compared to those who are not a part of it. It would help deem whether this program is worth promoting and showcasing or if some restructuring would be needed. 