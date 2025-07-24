# DeltaForce ID 数据文件说明

角色、枪械/载具皮肤id与图片链接的对应关系为:
> https://playerhub.df.qq.com/playerhub/60004/object/p_{ID}.png
> 
> 参考character_images.json文件,替换{ID}为对应的id
>
> 例如: 
> 
> >威龙:https://playerhub.df.qq.com/playerhub/60004/object/p_88000000025.png
> > 
> > 沙漠之鹰-白鹰军团:https://playerhub.df.qq.com/playerhub/60004/object/p_28070450001.png
>

地图图片：

> 你可以尝试访问 https://df.qq.com/cp/a20240729directory 进行获取
> 
> 或暂时先使用已拼接好的图片：
> 
> (暂时只有整体地图，地图具体分层图片未进行处理)
> 
> 零号大坝：
> https://www.drluo.top/img/df/map/lhdb.jpg
> 
> 长弓溪谷：
> https://www.drluo.top/img/df/map/cgxg.jpg
> 
> 巴克什：
> https://www.drluo.top/img/df/map/bks.jpg
> 
> 航天基地：
> https://www.drluo.top/img/df/map/htjd.jpg
> 
> 潮汐监狱：
> https://www.drluo.top/img/df/map/cxjy.jpg
> 
> 如果你对github的访问速度较快，可以考虑使用仓库链接：
> https://github.com/luoy-oss/luoy-oss.github.io/raw/main/img/df/map/lhdb.jpg

### characters_id_map.json
> 所有角色的ID与图片id
> "ID": "图片id"

```json
{
    "40005": 88000000028,
    "10010": 88000000025,
}
```

### characters_name_map.json
> 所有角色的ID与对应名称
> "ID": "角色名称"

```json
{
    "40005": "露娜",
    "10010": "威龙",
}
```

### map_id.json
> 游戏内所有地图的ID与对应名称
> "ID": "地图名称"

```json
{
  "1901": "长弓溪谷-常规",
  "1902": "长弓溪谷-机密"
}
```

### score_classification_sol.json

> 烽火地带模式下的积分段位对应关系
> "积分": "段位"

```json
{
  "1149": "青铜Ⅲ",
  "1299": "青铜Ⅱ"
}
```

### score_classification_tdm.json
> 全面战场模式下的积分段位对应关系
> "积分": "段位"

```json
{
  "149": "列兵Ⅲ",
  "299": "列兵Ⅱ"
}
```

### vehicle_skins.json
> 所有载具的皮肤ID与对应名称
> "ID": "皮肤名称"

```json
{
    "41001140003": "LAV-G1步战车-纷争",
    "41001140001": "M1A4主战坦克-纷争",
}
```

### weapon_skins.json
> 所有武器的皮肤ID与对应名称
> "ID": "皮肤名称"

```json
{
    "28011350001": "K416突击步枪-尖峰行动",
    "28011550001": "AUG突击步枪-尖峰行动",
}
```

## 使用说明
1. 所有JSON文件均为UTF-8编码
2. 数据格式均为键值对映射
