# IPO

LeetCode Q # 502.

Suppose LeetCode will start its IPO soon. In order to sell a good price of its shares to Venture Capital, LeetCode would like to work on some projects to increase its capital before the IPO. Since it has limited resources, it can only finish at most k distinct projects before the IPO. Help LeetCode design the best way to maximize its total capital after finishing at most k distinct projects.

You are given n projects where the ith project has a pure profit profits[i] and a minimum capital of capital[i] is needed to start it.

Initially, you have w capital. When you finish a project, you will obtain its pure profit and the profit will be added to your total capital.

Pick a list of at most k distinct projects from given projects to maximize your final capital, and return the final maximized capital.

The answer is guaranteed to fit in a 32-bit signed integer.

Example 1:

>Input: k = 2, w = 0, profits = [1,2,3], capital = [0,1,1]</br>
>Output: 4</br>
>Explanation: Since your initial capital is 0, you can only start the project indexed 0.</br>
>After finishing it you will obtain profit 1 and your capital becomes 1.</br>
>With capital 1, you can either start the project indexed 1 or the project indexed 2.</br>
>Since you can choose at most 2 projects, you need to finish the project indexed 2 to get the maximum capital.</br>
>Therefore, output the final maximized capital, which is 0 + 1 + 3 = 4.

Example 2:

>Input: k = 3, w = 0, profits = [1,2,3], capital = [0,1,2]</br>
>Output: 6

My Solution Analysis:

<div align = "center">

  ![image](https://github.com/xo-azeem/IPO-LeetCode/assets/171427226/850fe579-67b5-4ab8-9986-a85d407b7492)

  Time complexity: O(n).</br>Space complexity: O(1).
</div>
