## 部署步骤
1. Fork本仓库
2. 配置GitHub Actions所需的参数
    - 点击仓库下的Settings->Secrets->New repository secret, 分别添加以下secret
        - Name:LEETCODE_EMAIL  Value:你的LeetCode账号
        - Name:LEETCODE_PASSWORD  Value:你的LeetCode密码
    - 点击[tokens](https://github.com/settings/tokens)->Generate new token
        - Note:GITHUB_TOKEN
        - Select scopes:建议全部勾选

> 重刷次数的计算规则为: 累计所有提交通过且互为不同一天的记录次数

| 最近提交时间 | 题目 | 题目难度 | 提交次数| 重刷次数 |
| ---- | ---- | ---- | ---- | ---- |
| 2020-12-04 15:48 | [#5 最长回文子串](https://leetcode-cn.com/problems/longest-palindromic-substring) | MEDIUM | 12 | **5** |
| 2020-12-04 15:27 | [#3 无重复字符的最长子串](https://leetcode-cn.com/problems/longest-substring-without-repeating-characters) | MEDIUM | 17 | **8** |
| 2020-12-04 15:24 | [#2 两数相加](https://leetcode-cn.com/problems/add-two-numbers) | MEDIUM | 8 | **6** |
| 2020-12-04 15:17 | [#1 两数之和](https://leetcode-cn.com/problems/two-sum) | EASY | 14 | **11** |
| 2020-11-01 03:48 | [#1640 能否连接形成数组](https://leetcode-cn.com/problems/check-array-formation-through-concatenation) | EASY | 1 | 1 |
| 2020-11-01 03:17 | [#1642 可以到达的最远建筑](https://leetcode-cn.com/problems/furthest-building-you-can-reach) | MEDIUM | 1 | 1 |
| 2020-11-01 02:59 | [#1641 统计字典序元音字符串的数目](https://leetcode-cn.com/problems/count-sorted-vowel-strings) | MEDIUM | 1 | 1 |
| 2020-10-18 03:47 | [#1626 无矛盾的最佳球队](https://leetcode-cn.com/problems/best-team-with-no-conflicts) | MEDIUM | 2 | 1 |
| 2020-10-18 02:52 | [#1624 两个相同字符之间的最长子字符串](https://leetcode-cn.com/problems/largest-substring-between-two-equal-characters) | EASY | 1 | 1 |
| 2020-10-17 01:46 | [#49 字母异位词分组](https://leetcode-cn.com/problems/group-anagrams) | MEDIUM | 5 | **4** |
| 2020-10-17 01:36 | [#38 外观数列](https://leetcode-cn.com/problems/count-and-say) | MEDIUM | 6 | **4** |
| 2020-10-17 01:25 | [#117 填充每个节点的下一个右侧节点指针 II](https://leetcode-cn.com/problems/populating-next-right-pointers-in-each-node-ii) | MEDIUM | 1 | 1 |
| 2020-10-17 01:07 | [#87 扰乱字符串](https://leetcode-cn.com/problems/scramble-string) | HARD | 2 | 1 |
| 2020-10-14 10:46 | [#146 LRU 缓存机制](https://leetcode-cn.com/problems/lru-cache) | MEDIUM | 6 | **3** |
| 2020-09-28 02:56 | [#14 最长公共前缀](https://leetcode-cn.com/problems/longest-common-prefix) | EASY | 2 | 1 |
| 2020-09-27 15:15 | [#剑指 Offer 09 用两个栈实现队列](https://leetcode-cn.com/problems/yong-liang-ge-zhan-shi-xian-dui-lie-lcof) | EASY | 2 | **2** |
| 2020-09-27 15:10 | [#110 平衡二叉树](https://leetcode-cn.com/problems/balanced-binary-tree) | EASY | 2 | **2** |
| 2020-09-27 14:51 | [#236 二叉树的最近公共祖先](https://leetcode-cn.com/problems/lowest-common-ancestor-of-a-binary-tree) | MEDIUM | 7 | **6** |
| 2020-09-17 13:02 | [#22 括号生成](https://leetcode-cn.com/problems/generate-parentheses) | MEDIUM | 2 | **2** |
| 2020-09-12 04:21 | [#37 解数独](https://leetcode-cn.com/problems/sudoku-solver) | HARD | 12 | **7** |
| 2020-08-30 03:08 | [#1567 乘积为正数的最长子数组长度](https://leetcode-cn.com/problems/maximum-length-of-subarray-with-positive-product) | MEDIUM | 1 | 1 |
| 2020-08-30 02:54 | [#1566 重复至少 K 次且长度为 M 的模式](https://leetcode-cn.com/problems/detect-pattern-of-length-m-repeated-k-or-more-times) | EASY | 1 | 1 |
| 2020-08-28 09:14 | [#409 最长回文串](https://leetcode-cn.com/problems/longest-palindrome) | EASY | 4 | 1 |
| 2020-08-25 04:25 | [#237 删除链表中的节点](https://leetcode-cn.com/problems/delete-node-in-a-linked-list) | EASY | 4 | **4** |
| 2020-08-25 04:24 | [#19 删除链表的倒数第 N 个结点](https://leetcode-cn.com/problems/remove-nth-node-from-end-of-list) | MEDIUM | 11 | **9** |
| 2020-08-25 03:59 | [#34 在排序数组中查找元素的第一个和最后一个位置](https://leetcode-cn.com/problems/find-first-and-last-position-of-element-in-sorted-array) | MEDIUM | 11 | **5** |
| 2020-08-25 03:54 | [#35 搜索插入位置](https://leetcode-cn.com/problems/search-insert-position) | EASY | 16 | **7** |
| 2020-08-25 03:47 | [#69 x 的平方根](https://leetcode-cn.com/problems/sqrtx) | EASY | 25 | **9** |
| 2020-08-24 14:55 | [#10 正则表达式匹配](https://leetcode-cn.com/problems/regular-expression-matching) | HARD | 3 | **2** |
| 2020-08-24 14:38 | [#664 奇怪的打印机](https://leetcode-cn.com/problems/strange-printer) | HARD | 2 | 1 |
| 2020-08-19 12:47 | [#1277 统计全为 1 的正方形子矩阵](https://leetcode-cn.com/problems/count-square-submatrices-with-all-ones) | MEDIUM | 1 | 1 |
| 2020-08-16 06:39 | [#1553 吃掉 N 个橘子的最少天数](https://leetcode-cn.com/problems/minimum-number-of-days-to-eat-n-oranges) | HARD | 2 | 1 |
| 2020-08-16 03:17 | [#1552 两球之间的磁力](https://leetcode-cn.com/problems/magnetic-force-between-two-balls) | MEDIUM | 1 | 1 |
| 2020-08-16 02:40 | [#1551 使数组中所有元素相等的最小操作数](https://leetcode-cn.com/problems/minimum-operations-to-make-array-equal) | MEDIUM | 1 | 1 |
| 2020-08-16 02:32 | [#1550 存在连续三个奇数的数组](https://leetcode-cn.com/problems/three-consecutive-odds) | EASY | 1 | 1 |
| 2020-08-11 14:14 | [#45 跳跃游戏 II](https://leetcode-cn.com/problems/jump-game-ii) | MEDIUM | 1 | 1 |
| 2020-08-09 04:03 | [#1544 整理字符串](https://leetcode-cn.com/problems/make-the-string-great) | EASY | 5 | 1 |
| 2020-08-09 03:00 | [#1545 找出第 N 个二进制字符串中的第 K 位](https://leetcode-cn.com/problems/find-kth-bit-in-nth-binary-string) | MEDIUM | 1 | 1 |
| 2020-08-07 07:04 | [#剑指 Offer 34 二叉树中和为某一值的路径](https://leetcode-cn.com/problems/er-cha-shu-zhong-he-wei-mou-yi-zhi-de-lu-jing-lcof) | MEDIUM | 1 | 1 |
| 2020-08-07 07:00 | [#剑指 Offer 33 二叉搜索树的后序遍历序列](https://leetcode-cn.com/problems/er-cha-sou-suo-shu-de-hou-xu-bian-li-xu-lie-lcof) | MEDIUM | 1 | 1 |
| 2020-08-07 06:56 | [#剑指 Offer 32 - III 从上到下打印二叉树 III](https://leetcode-cn.com/problems/cong-shang-dao-xia-da-yin-er-cha-shu-iii-lcof) | MEDIUM | 1 | 1 |
| 2020-08-07 06:53 | [#剑指 Offer 32 - II 从上到下打印二叉树 II](https://leetcode-cn.com/problems/cong-shang-dao-xia-da-yin-er-cha-shu-ii-lcof) | EASY | 1 | 1 |
| 2020-08-07 06:51 | [#剑指 Offer 32 - I 从上到下打印二叉树](https://leetcode-cn.com/problems/cong-shang-dao-xia-da-yin-er-cha-shu-lcof) | MEDIUM | 1 | 1 |
| 2020-08-07 06:50 | [#剑指 Offer 31 栈的压入、弹出序列](https://leetcode-cn.com/problems/zhan-de-ya-ru-dan-chu-xu-lie-lcof) | MEDIUM | 2 | 1 |
| 2020-08-07 06:46 | [#剑指 Offer 30 包含min函数的栈](https://leetcode-cn.com/problems/bao-han-minhan-shu-de-zhan-lcof) | EASY | 1 | 1 |
| 2020-08-07 06:40 | [#剑指 Offer 28 对称的二叉树](https://leetcode-cn.com/problems/dui-cheng-de-er-cha-shu-lcof) | EASY | 1 | 1 |
| 2020-08-07 06:38 | [#剑指 Offer 27 二叉树的镜像](https://leetcode-cn.com/problems/er-cha-shu-de-jing-xiang-lcof) | EASY | 1 | 1 |
| 2020-08-07 06:33 | [#剑指 Offer 26 树的子结构](https://leetcode-cn.com/problems/shu-de-zi-jie-gou-lcof) | MEDIUM | 3 | 1 |
| 2020-08-07 06:21 | [#剑指 Offer 25 合并两个排序的链表](https://leetcode-cn.com/problems/he-bing-liang-ge-pai-xu-de-lian-biao-lcof) | EASY | 1 | 1 |
| 2020-08-07 06:19 | [#剑指 Offer 24 反转链表](https://leetcode-cn.com/problems/fan-zhuan-lian-biao-lcof) | EASY | 3 | 1 |
| 2020-08-07 06:14 | [#剑指 Offer 22 链表中倒数第k个节点](https://leetcode-cn.com/problems/lian-biao-zhong-dao-shu-di-kge-jie-dian-lcof) | EASY | 1 | 1 |
| 2020-08-07 06:11 | [#剑指 Offer 21 调整数组顺序使奇数位于偶数前面](https://leetcode-cn.com/problems/diao-zheng-shu-zu-shun-xu-shi-qi-shu-wei-yu-ou-shu-qian-mian-lcof) | EASY | 2 | 1 |
| 2020-08-06 10:21 | [#剑指 Offer 19 正则表达式匹配](https://leetcode-cn.com/problems/zheng-ze-biao-da-shi-pi-pei-lcof) | HARD | 1 | 1 |
| 2020-08-06 09:54 | [#剑指 Offer 18 删除链表的节点](https://leetcode-cn.com/problems/shan-chu-lian-biao-de-jie-dian-lcof) | EASY | 1 | 1 |
| 2020-08-06 09:46 | [#剑指 Offer 17 打印从1到最大的n位数](https://leetcode-cn.com/problems/da-yin-cong-1dao-zui-da-de-nwei-shu-lcof) | EASY | 1 | 1 |
| 2020-08-06 09:42 | [#剑指 Offer 16 数值的整数次方](https://leetcode-cn.com/problems/shu-zhi-de-zheng-shu-ci-fang-lcof) | MEDIUM | 4 | 1 |
| 2020-08-06 09:13 | [#剑指 Offer 15 二进制中1的个数](https://leetcode-cn.com/problems/er-jin-zhi-zhong-1de-ge-shu-lcof) | EASY | 1 | 1 |
| 2020-08-06 08:40 | [#剑指 Offer 14- II 剪绳子 II](https://leetcode-cn.com/problems/jian-sheng-zi-ii-lcof) | MEDIUM | 2 | 1 |
| 2020-08-06 07:36 | [#剑指 Offer 14- I 剪绳子](https://leetcode-cn.com/problems/jian-sheng-zi-lcof) | MEDIUM | 2 | 1 |
| 2020-08-05 13:28 | [#剑指 Offer 13 机器人的运动范围](https://leetcode-cn.com/problems/ji-qi-ren-de-yun-dong-fan-wei-lcof) | MEDIUM | 3 | 1 |
| 2020-08-05 13:12 | [#剑指 Offer 12 矩阵中的路径](https://leetcode-cn.com/problems/ju-zhen-zhong-de-lu-jing-lcof) | MEDIUM | 1 | 1 |
| 2020-08-05 12:41 | [#剑指 Offer 11 旋转数组的最小数字](https://leetcode-cn.com/problems/xuan-zhuan-shu-zu-de-zui-xiao-shu-zi-lcof) | EASY | 2 | 1 |
| 2020-08-05 12:35 | [#剑指 Offer 10- II 青蛙跳台阶问题](https://leetcode-cn.com/problems/qing-wa-tiao-tai-jie-wen-ti-lcof) | EASY | 3 | 1 |
| 2020-08-05 12:23 | [#剑指 Offer 10- I 斐波那契数列](https://leetcode-cn.com/problems/fei-bo-na-qi-shu-lie-lcof) | EASY | 2 | 1 |
| 2020-08-05 12:14 | [#剑指 Offer 07 重建二叉树](https://leetcode-cn.com/problems/zhong-jian-er-cha-shu-lcof) | MEDIUM | 2 | 1 |
| 2020-08-05 11:59 | [#剑指 Offer 06 从尾到头打印链表](https://leetcode-cn.com/problems/cong-wei-dao-tou-da-yin-lian-biao-lcof) | EASY | 1 | 1 |
| 2020-08-05 11:58 | [#剑指 Offer 05 替换空格](https://leetcode-cn.com/problems/ti-huan-kong-ge-lcof) | EASY | 1 | 1 |
| 2020-08-05 11:57 | [#剑指 Offer 04 二维数组中的查找](https://leetcode-cn.com/problems/er-wei-shu-zu-zhong-de-cha-zhao-lcof) | MEDIUM | 1 | 1 |
| 2020-08-05 11:54 | [#剑指 Offer 03 数组中重复的数字](https://leetcode-cn.com/problems/shu-zu-zhong-zhong-fu-de-shu-zi-lcof) | EASY | 1 | 1 |
| 2020-08-05 09:21 | [#109 有序链表转换二叉搜索树](https://leetcode-cn.com/problems/convert-sorted-list-to-binary-search-tree) | MEDIUM | 2 | 1 |
| 2020-07-29 15:01 | [#1143 最长公共子序列](https://leetcode-cn.com/problems/longest-common-subsequence) | MEDIUM | 1 | 1 |
| 2020-07-29 05:00 | [#704 二分查找](https://leetcode-cn.com/problems/binary-search) | EASY | 1 | 1 |
| 2020-07-29 04:54 | [#41 缺失的第一个正数](https://leetcode-cn.com/problems/first-missing-positive) | HARD | 1 | 1 |
| 2020-07-29 04:27 | [#8 字符串转换整数 (atoi)](https://leetcode-cn.com/problems/string-to-integer-atoi) | MEDIUM | 9 | 1 |
| 2020-07-29 01:58 | [#160 相交链表](https://leetcode-cn.com/problems/intersection-of-two-linked-lists) | EASY | 8 | **4** |
| 2020-07-29 01:50 | [#124 二叉树中的最大路径和](https://leetcode-cn.com/problems/binary-tree-maximum-path-sum) | HARD | 19 | **6** |
| 2020-07-29 01:36 | [#100 相同的树](https://leetcode-cn.com/problems/same-tree) | EASY | 1 | 1 |
| 2020-07-29 01:21 | [#206 反转链表](https://leetcode-cn.com/problems/reverse-linked-list) | EASY | 13 | **8** |
| 2020-07-29 00:50 | [#876 链表的中间结点](https://leetcode-cn.com/problems/middle-of-the-linked-list) | EASY | 1 | 1 |
| 2020-07-28 04:38 | [#283 移动零](https://leetcode-cn.com/problems/move-zeroes) | EASY | 2 | 1 |
| 2020-07-28 04:06 | [#20 有效的括号](https://leetcode-cn.com/problems/valid-parentheses) | EASY | 2 | 1 |
| 2020-07-28 03:39 | [#101 对称二叉树](https://leetcode-cn.com/problems/symmetric-tree) | EASY | 15 | **10** |
| 2020-07-28 03:34 | [#347 前 K 个高频元素](https://leetcode-cn.com/problems/top-k-frequent-elements) | MEDIUM | 1 | 1 |
| 2020-07-28 03:24 | [#剑指 Offer 42 连续子数组的最大和](https://leetcode-cn.com/problems/lian-xu-zi-shu-zu-de-zui-da-he-lcof) | EASY | 1 | 1 |
| 2020-07-27 05:31 | [#113 路径总和 II](https://leetcode-cn.com/problems/path-sum-ii) | MEDIUM | 2 | 1 |
| 2020-07-27 05:16 | [#199 二叉树的右视图](https://leetcode-cn.com/problems/binary-tree-right-side-view) | MEDIUM | 1 | 1 |
| 2020-07-27 05:10 | [#415 字符串相加](https://leetcode-cn.com/problems/add-strings) | EASY | 1 | 1 |
| 2020-07-27 03:13 | [#102 二叉树的层序遍历](https://leetcode-cn.com/problems/binary-tree-level-order-traversal) | MEDIUM | 7 | **6** |
| 2020-07-27 01:08 | [#剑指 Offer 29 顺时针打印矩阵](https://leetcode-cn.com/problems/shun-shi-zhen-da-yin-ju-zhen-lcof) | EASY | 2 | **2** |
| 2020-07-27 01:08 | [#814 二叉树剪枝](https://leetcode-cn.com/problems/binary-tree-pruning) | MEDIUM | 3 | **2** |
| 2020-07-27 01:03 | [#445 两数相加 II](https://leetcode-cn.com/problems/add-two-numbers-ii) | MEDIUM | 4 | **2** |
| 2020-07-27 00:39 | [#23 合并K个升序链表](https://leetcode-cn.com/problems/merge-k-sorted-lists) | HARD | 5 | **2** |
| 2020-07-26 14:18 | [#509 斐波那契数](https://leetcode-cn.com/problems/fibonacci-number) | EASY | 2 | 1 |
| 2020-07-26 10:02 | [#4 寻找两个正序数组的中位数](https://leetcode-cn.com/problems/median-of-two-sorted-arrays) | HARD | 1 | 1 |
| 2020-07-26 09:52 | [#63 不同路径 II](https://leetcode-cn.com/problems/unique-paths-ii) | MEDIUM | 21 | **7** |
| 2020-07-26 09:42 | [#62 不同路径](https://leetcode-cn.com/problems/unique-paths) | MEDIUM | 1 | 1 |
| 2020-07-26 04:33 | [#104 二叉树的最大深度](https://leetcode-cn.com/problems/maximum-depth-of-binary-tree) | EASY | 2 | **2** |
| 2020-07-25 03:02 | [#122 买卖股票的最佳时机 II](https://leetcode-cn.com/problems/best-time-to-buy-and-sell-stock-ii) | EASY | 3 | **3** |
| 2020-07-25 03:00 | [#72 编辑距离](https://leetcode-cn.com/problems/edit-distance) | HARD | 7 | **6** |
| 2020-07-23 03:44 | [#96 不同的二叉搜索树](https://leetcode-cn.com/problems/unique-binary-search-trees) | MEDIUM | 1 | 1 |
| 2020-07-23 02:08 | [#312 戳气球](https://leetcode-cn.com/problems/burst-balloons) | HARD | 1 | 1 |
| 2020-07-22 01:31 | [#123 买卖股票的最佳时机 III](https://leetcode-cn.com/problems/best-time-to-buy-and-sell-stock-iii) | HARD | 6 | **2** |
| 2020-07-22 01:07 | [#309 最佳买卖股票时机含冷冻期](https://leetcode-cn.com/problems/best-time-to-buy-and-sell-stock-with-cooldown) | MEDIUM | 3 | 1 |
| 2020-07-22 00:36 | [#188 买卖股票的最佳时机 IV](https://leetcode-cn.com/problems/best-time-to-buy-and-sell-stock-iv) | HARD | 7 | 1 |
| 2020-07-21 23:29 | [#213 打家劫舍 II](https://leetcode-cn.com/problems/house-robber-ii) | MEDIUM | 3 | **2** |
| 2020-07-21 23:16 | [#198 打家劫舍](https://leetcode-cn.com/problems/house-robber) | MEDIUM | 7 | **6** |
| 2020-07-21 04:14 | [#121 买卖股票的最佳时机](https://leetcode-cn.com/problems/best-time-to-buy-and-sell-stock) | EASY | 4 | **2** |
| 2020-07-21 03:05 | [#300 最长递增子序列](https://leetcode-cn.com/problems/longest-increasing-subsequence) | MEDIUM | 9 | **6** |
| 2020-07-21 03:01 | [#53 最大子序和](https://leetcode-cn.com/problems/maximum-subarray) | EASY | 18 | **10** |
| 2020-07-21 02:35 | [#1510 石子游戏 IV](https://leetcode-cn.com/problems/stone-game-iv) | HARD | 4 | **2** |
| 2020-07-20 04:06 | [#1515 服务中心的最佳位置](https://leetcode-cn.com/problems/best-position-for-a-service-centre) | HARD | 1 | 1 |
| 2020-07-20 03:14 | [#1507 转变日期格式](https://leetcode-cn.com/problems/reformat-date) | EASY | 3 | **2** |
| 2020-07-19 06:10 | [#52 N皇后 II](https://leetcode-cn.com/problems/n-queens-ii) | HARD | 10 | **5** |
| 2020-07-19 06:04 | [#473 火柴拼正方形](https://leetcode-cn.com/problems/matchsticks-to-square) | MEDIUM | 12 | **4** |
| 2020-07-19 05:40 | [#216 组合总和 III](https://leetcode-cn.com/problems/combination-sum-iii) | MEDIUM | 7 | **6** |
| 2020-07-19 05:22 | [#40 组合总和 II](https://leetcode-cn.com/problems/combination-sum-ii) | MEDIUM | 6 | 1 |
| 2020-07-19 02:51 | [#1518 换酒问题](https://leetcode-cn.com/problems/water-bottles) | EASY | 1 | 1 |
| 2020-07-19 01:53 | [#39 组合总和](https://leetcode-cn.com/problems/combination-sum) | MEDIUM | 4 | **3** |
| 2020-07-18 16:14 | [#1514 概率最大的路径](https://leetcode-cn.com/problems/path-with-maximum-probability) | MEDIUM | 2 | 1 |
| 2020-07-18 03:48 | [#1512 好数对的数目](https://leetcode-cn.com/problems/number-of-good-pairs) | EASY | 2 | 1 |
| 2020-07-17 03:00 | [#90 子集 II](https://leetcode-cn.com/problems/subsets-ii) | MEDIUM | 10 | **7** |
| 2020-07-17 01:42 | [#78 子集](https://leetcode-cn.com/problems/subsets) | MEDIUM | 7 | **6** |
| 2020-07-17 01:38 | [#47 全排列 II](https://leetcode-cn.com/problems/permutations-ii) | MEDIUM | 10 | **9** |
| 2020-07-17 01:29 | [#46 全排列](https://leetcode-cn.com/problems/permutations) | MEDIUM | 8 | **7** |
| 2020-07-17 01:24 | [#17 电话号码的字母组合](https://leetcode-cn.com/problems/letter-combinations-of-a-phone-number) | MEDIUM | 10 | **7** |
| 2020-07-17 01:14 | [#148 排序链表](https://leetcode-cn.com/problems/sort-list) | MEDIUM | 6 | **4** |
| 2020-07-16 04:33 | [#142 环形链表 II](https://leetcode-cn.com/problems/linked-list-cycle-ii) | MEDIUM | 7 | **3** |
| 2020-07-16 04:28 | [#138 复制带随机指针的链表](https://leetcode-cn.com/problems/copy-list-with-random-pointer) | MEDIUM | 1 | 1 |
| 2020-07-14 03:04 | [#1509 三次操作后最大值与最小值的最小差](https://leetcode-cn.com/problems/minimum-difference-between-largest-and-smallest-value-in-three-moves) | MEDIUM | 4 | 1 |
| 2020-07-14 02:50 | [#1508 子数组和排序后的区间和](https://leetcode-cn.com/problems/range-sum-of-sorted-subarray-sums) | MEDIUM | 2 | 1 |
| 2020-07-05 02:43 | [#1503 所有蚂蚁掉下来前的最后一刻](https://leetcode-cn.com/problems/last-moment-before-all-ants-fall-out-of-a-plank) | MEDIUM | 2 | 1 |
| 2020-07-05 02:33 | [#1502 判断能否形成等差数列](https://leetcode-cn.com/problems/can-make-arithmetic-progression-from-sequence) | EASY | 1 | 1 |
| 2020-07-01 01:43 | [#120 三角形最小路径和](https://leetcode-cn.com/problems/triangle) | MEDIUM | 9 | **7** |
| 2020-07-01 01:21 | [#518 零钱兑换 II](https://leetcode-cn.com/problems/coin-change-2) | MEDIUM | 6 | **3** |
| 2020-07-01 01:13 | [#91 解码方法](https://leetcode-cn.com/problems/decode-ways) | MEDIUM | 12 | **6** |
| 2020-06-29 03:01 | [#79 单词搜索](https://leetcode-cn.com/problems/word-search) | MEDIUM | 9 | **6** |
| 2020-06-29 02:29 | [#239 滑动窗口最大值](https://leetcode-cn.com/problems/sliding-window-maximum) | HARD | 2 | **2** |
| 2020-06-29 02:00 | [#84 柱状图中最大的矩形](https://leetcode-cn.com/problems/largest-rectangle-in-histogram) | HARD | 5 | **2** |
| 2020-06-29 01:27 | [#32 最长有效括号](https://leetcode-cn.com/problems/longest-valid-parentheses) | HARD | 8 | **4** |
| 2020-06-29 01:21 | [#76 最小覆盖子串](https://leetcode-cn.com/problems/minimum-window-substring) | HARD | 8 | **5** |
| 2020-06-29 00:50 | [#26 删除有序数组中的重复项](https://leetcode-cn.com/problems/remove-duplicates-from-sorted-array) | EASY | 11 | **5** |
| 2020-06-29 00:45 | [#88 合并两个有序数组](https://leetcode-cn.com/problems/merge-sorted-array) | EASY | 8 | **6** |
| 2020-06-28 13:54 | [#42 接雨水](https://leetcode-cn.com/problems/trapping-rain-water) | HARD | 2 | **2** |
| 2020-06-28 11:48 | [#155 最小栈](https://leetcode-cn.com/problems/min-stack) | EASY | 5 | **4** |
| 2020-06-28 10:03 | [#167 两数之和 II - 输入有序数组](https://leetcode-cn.com/problems/two-sum-ii-input-array-is-sorted) | EASY | 7 | **4** |
| 2020-06-28 09:54 | [#1498 满足条件的子序列数目](https://leetcode-cn.com/problems/number-of-subsequences-that-satisfy-the-given-sum-condition) | MEDIUM | 1 | 1 |
| 2020-06-28 07:12 | [#1497 检查数组对是否可以被 k 整除](https://leetcode-cn.com/problems/check-if-array-pairs-are-divisible-by-k) | MEDIUM | 1 | 1 |
| 2020-06-28 06:32 | [#1496 判断路径是否相交](https://leetcode-cn.com/problems/path-crossing) | EASY | 2 | 1 |
| 2020-06-26 01:13 | [#684 冗余连接](https://leetcode-cn.com/problems/redundant-connection) | MEDIUM | 7 | **5** |
| 2020-06-26 01:05 | [#547 省份数量](https://leetcode-cn.com/problems/number-of-provinces) | MEDIUM | 9 | **5** |
| 2020-06-26 01:00 | [#560 和为K的子数组](https://leetcode-cn.com/problems/subarray-sum-equals-k) | MEDIUM | 10 | **5** |
| 2020-06-26 00:37 | [#652 寻找重复的子树](https://leetcode-cn.com/problems/find-duplicate-subtrees) | MEDIUM | 4 | **4** |
| 2020-06-26 00:21 | [#706 设计哈希映射](https://leetcode-cn.com/problems/design-hashmap) | EASY | 9 | **6** |
| 2020-06-25 23:37 | [#187 重复的DNA序列](https://leetcode-cn.com/problems/repeated-dna-sequences) | MEDIUM | 9 | **4** |
| 2020-06-18 22:52 | [#173 二叉搜索树迭代器](https://leetcode-cn.com/problems/binary-search-tree-iterator) | MEDIUM | 5 | **4** |
| 2020-06-18 22:44 | [#543 二叉树的直径](https://leetcode-cn.com/problems/diameter-of-binary-tree) | EASY | 10 | **6** |
| 2020-06-18 22:41 | [#297 二叉树的序列化与反序列化](https://leetcode-cn.com/problems/serialize-and-deserialize-binary-tree) | HARD | 5 | **3** |
| 2020-06-18 22:33 | [#94 二叉树的中序遍历](https://leetcode-cn.com/problems/binary-tree-inorder-traversal) | EASY | 18 | **10** |
| 2020-06-18 22:31 | [#98 验证二叉搜索树](https://leetcode-cn.com/problems/validate-binary-search-tree) | MEDIUM | 21 | **9** |
| 2020-06-18 10:07 | [#105 从前序与中序遍历序列构造二叉树](https://leetcode-cn.com/problems/construct-binary-tree-from-preorder-and-inorder-traversal) | MEDIUM | 6 | **5** |
| 2020-06-14 14:24 | [#1480 一维数组的动态和](https://leetcode-cn.com/problems/running-sum-of-1d-array) | EASY | 2 | 1 |
| 2020-06-12 09:09 | [#141 环形链表](https://leetcode-cn.com/problems/linked-list-cycle) | EASY | 5 | **2** |
| 2020-06-12 07:22 | [#24 两两交换链表中的节点](https://leetcode-cn.com/problems/swap-nodes-in-pairs) | MEDIUM | 8 | **5** |
| 2020-06-12 07:06 | [#83 删除排序链表中的重复元素](https://leetcode-cn.com/problems/remove-duplicates-from-sorted-list) | EASY | 9 | **6** |
| 2020-06-11 01:40 | [#92 反转链表 II](https://leetcode-cn.com/problems/reverse-linked-list-ii) | MEDIUM | 6 | **4** |
| 2020-06-11 01:13 | [#61 旋转链表](https://leetcode-cn.com/problems/rotate-list) | MEDIUM | 16 | **7** |
| 2020-06-07 05:35 | [#1472 设计浏览器历史记录](https://leetcode-cn.com/problems/design-browser-history) | MEDIUM | 1 | 1 |
| 2020-06-07 03:32 | [#1471 数组中的 k 个最强值](https://leetcode-cn.com/problems/the-k-strongest-values-in-an-array) | MEDIUM | 1 | 1 |
| 2020-06-07 03:17 | [#1470 重新排列数组](https://leetcode-cn.com/problems/shuffle-the-array) | EASY | 1 | 1 |
| 2020-06-06 02:05 | [#692 前K个高频单词](https://leetcode-cn.com/problems/top-k-frequent-words) | MEDIUM | 2 | 1 |
| 2020-06-05 12:59 | [#352 将数据流变为多个不相交区间](https://leetcode-cn.com/problems/data-stream-as-disjoint-intervals) | HARD | 4 | 1 |
| 2020-06-05 12:06 | [#295 数据流的中位数](https://leetcode-cn.com/problems/find-median-from-data-stream) | HARD | 1 | 1 |
| 2020-06-05 04:07 | [#918 环形子数组的最大和](https://leetcode-cn.com/problems/maximum-sum-circular-subarray) | MEDIUM | 4 | 1 |
| 2020-06-02 07:22 | [#151 翻转字符串里的单词](https://leetcode-cn.com/problems/reverse-words-in-a-string) | MEDIUM | 10 | **3** |
| 2020-06-01 02:06 | [#208 实现 Trie (前缀树)](https://leetcode-cn.com/problems/implement-trie-prefix-tree) | MEDIUM | 3 | **2** |
| 2020-06-01 01:27 | [#6 Z 字形变换](https://leetcode-cn.com/problems/zigzag-conversion) | MEDIUM | 6 | **3** |
| 2020-05-31 14:28 | [#1466 重新规划路线](https://leetcode-cn.com/problems/reorder-routes-to-make-all-paths-lead-to-the-city-zero) | MEDIUM | 3 | 1 |
| 2020-05-31 06:59 | [#929 独特的电子邮件地址](https://leetcode-cn.com/problems/unique-email-addresses) | EASY | 5 | **3** |
| 2020-05-31 04:17 | [#1465 切割后面积最大的蛋糕](https://leetcode-cn.com/problems/maximum-area-of-a-piece-of-cake-after-horizontal-and-vertical-cuts) | MEDIUM | 5 | 1 |
| 2020-05-31 03:45 | [#1464 数组中两元素的最大乘积](https://leetcode-cn.com/problems/maximum-product-of-two-elements-in-an-array) | EASY | 1 | 1 |
| 2020-05-30 15:01 | [#1460 通过翻转子数组使两个数组相等](https://leetcode-cn.com/problems/make-two-arrays-equal-by-reversing-sub-arrays) | EASY | 2 | 1 |
| 2020-05-28 02:02 | [#275 H 指数 II](https://leetcode-cn.com/problems/h-index-ii) | MEDIUM | 7 | **2** |
| 2020-05-28 01:47 | [#287 寻找重复数](https://leetcode-cn.com/problems/find-the-duplicate-number) | MEDIUM | 2 | **2** |
| 2020-05-28 01:43 | [#162 寻找峰值](https://leetcode-cn.com/problems/find-peak-element) | MEDIUM | 15 | **4** |
| 2020-05-28 01:34 | [#278 第一个错误的版本](https://leetcode-cn.com/problems/first-bad-version) | EASY | 6 | **3** |
| 2020-05-28 01:31 | [#33 搜索旋转排序数组](https://leetcode-cn.com/problems/search-in-rotated-sorted-array) | MEDIUM | 6 | **3** |
| 2020-05-28 01:21 | [#153 寻找旋转排序数组中的最小值](https://leetcode-cn.com/problems/find-minimum-in-rotated-sorted-array) | MEDIUM | 6 | **4** |
| 2020-05-28 01:16 | [#74 搜索二维矩阵](https://leetcode-cn.com/problems/search-a-2d-matrix) | MEDIUM | 11 | **7** |
| 2020-05-25 10:06 | [#1458 两个子序列的最大点积](https://leetcode-cn.com/problems/max-dot-product-of-two-subsequences) | HARD | 1 | 1 |
| 2020-05-25 09:49 | [#1456 定长子串中元音的最大数目](https://leetcode-cn.com/problems/maximum-number-of-vowels-in-a-substring-of-given-length) | MEDIUM | 4 | **2** |
| 2020-05-25 09:42 | [#1455 检查单词是否为句中其他单词的前缀](https://leetcode-cn.com/problems/check-if-a-word-occurs-as-a-prefix-of-any-word-in-a-sentence) | EASY | 2 | **2** |
| 2020-05-24 03:17 | [#1457 二叉树中的伪回文路径](https://leetcode-cn.com/problems/pseudo-palindromic-paths-in-a-binary-tree) | MEDIUM | 1 | 1 |
| 2020-04-19 03:51 | [#1417 重新格式化字符串](https://leetcode-cn.com/problems/reformat-the-string) | EASY | 1 | 1 |
| 2019-10-17 02:01 | [#273 整数转换英文表示](https://leetcode-cn.com/problems/integer-to-english-words) | HARD | 3 | 1 |
| 2019-10-16 23:12 | [#165 比较版本号](https://leetcode-cn.com/problems/compare-version-numbers) | MEDIUM | 6 | **2** |
| 2019-04-27 10:43 | [#653 两数之和 IV - 输入 BST](https://leetcode-cn.com/problems/two-sum-iv-input-is-a-bst) | EASY | 5 | **2** |
| 2019-04-27 08:40 | [#331 验证二叉树的前序序列化](https://leetcode-cn.com/problems/verify-preorder-serialization-of-a-binary-tree) | MEDIUM | 1 | 1 |
| 2019-04-25 01:15 | [#145 二叉树的后序遍历](https://leetcode-cn.com/problems/binary-tree-postorder-traversal) | EASY | 1 | 1 |
| 2019-04-14 09:13 | [#1056 易混淆数](https://leetcode-cn.com/problems/confusing-number) | EASY | 2 | 1 |
| 2019-04-12 12:30 | [#147 对链表进行插入排序](https://leetcode-cn.com/problems/insertion-sort-list) | MEDIUM | 2 | 1 |
| 2019-04-10 10:45 | [#143 重排链表](https://leetcode-cn.com/problems/reorder-list) | MEDIUM | 3 | 1 |
| 2019-04-04 02:05 | [#21 合并两个有序链表](https://leetcode-cn.com/problems/merge-two-sorted-lists) | EASY | 1 | 1 |
| 2019-03-08 11:11 | [#11 盛最多水的容器](https://leetcode-cn.com/problems/container-with-most-water) | MEDIUM | 1 | 1 |
| 2019-03-08 00:32 | [#9 回文数](https://leetcode-cn.com/problems/palindrome-number) | EASY | 1 | 1 |
| 2019-03-05 02:12 | [#7 整数反转](https://leetcode-cn.com/problems/reverse-integer) | EASY | 4 | 1 |
