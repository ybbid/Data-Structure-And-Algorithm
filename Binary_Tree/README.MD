1.树(tree):非线性数据结构
    非线性：1.树
            2.图
    术语：1.根结点(root):树中没有前驱结点
                        ！一个树中只有一个根结点
          2.叶子结点(leaf):没有后继的结点
                        ！一棵树中可以有多个叶子结点
          3.双亲结点，子女结点:双亲结点是子女结点的前驱，子女结点是双亲结点的后继
                        ！根结点无双亲
                        ！叶子结点无后继
                        ！除了根结点外，向上只有一个双亲
                        ！除叶子结点外剩余结点向下可以有多个（含一个）子女
          4.兄弟结点：同一个双亲结点的子女结点之间互称兄弟结点
          5.度：结点的度：一个结点的子女个数（叶子结点度为0）
                树度：度值最大的结点的度,一个树的度值为k，则为k叉树
          6。树的深度：树的层次数
2.二叉树：度值最大为2的树
    树状结构：
        1.有且只有一个结点无前驱：根结点
        2.可有多个结点无后继：叶子结点
        3.除根和叶子之外，其余结点只有一个双亲，可有多个后继

    1.形态：
        1.空二叉树：没有任何结点
        2.只有根
        3.只有左子女
        4.只有右子女
        5.左右都有子女
    2.数据结构表示：
        1.数据集合：二元组表示法
        DATA = {A, B, C, D, E, F, G, H, I, J}
        Relation = {<A, B>, <A, C>}
        2.广义表表示：根结点（左子女， 右子女）
    3.二叉树的性质：
        1.任意一棵非空二叉树的叶子结点总比双分支结点多一个

