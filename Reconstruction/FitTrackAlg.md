# FitTrackAlg
- 给算法添加几何描述文件gdml
  - gdml文件是用于描述探测器的文件，包括探测器的体积(volume)、材料(material)、层次结构以及放置等信息。
    - 体积（volume）：探测器的各个部件。
    - 材料（material）：探测器各个部件的材料，反映物质效应。
    - 层次结构：volume之间的包含/不包含关系。
    - 放置：各个volume之间的摆放、几何关系等。

- 算法读入数据的方式
  - 读入的col：cantrackcol
  - 源码：
    - auto CanTracks = getROColl(CanTrackCollection, "CanTrackCol");  这里表示只读 
      auto CanTracks = getRWColl(CanTrackCollection, "CanTrackCol");   这里表示读写
