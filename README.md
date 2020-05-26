# dophin-social-network-GCN-embedding
Dolphin数据集是 D.Lusseau 等人使用长达 7 年的时间观察新西兰 Doubtful Sound海峡 62 只海豚群体的交流情况而得到的海豚社会关系网络。这个网络具有 62 个节点，159 条边。节点表示海豚，边表示海豚间的频繁接触。本项目通过GCN对社交网络这种非结构化数据进行了graph embedding，最终在二维平面上进行了可视化。

# 文件说明
* dolphins.gml中为海豚社交网络的图数据
* dophin_gcn.py包括了数据的读取，GCN的应用和embedding结果的可视化
