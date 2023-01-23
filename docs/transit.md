## 可直接提供 Transit 的位置
通常情况下支持的连接类型：

**隧道：** `SIT` / `WireGuard` （**不支持 ZeroTier！**）

**物理：** `IX LAN` / 主机商提供的 `VLAN`

> MoeIX 未写在列表内
> 
> 除此之外的所有位置均可提供 Transit，但因没有当地上游，延迟会增加。

| Location | Upstream | IXP | v4 / v6 | Speed | Looking Glass | 
| :----: | :----: | :----: | :----: | :----: | :----: |
| Taipei | AS6939 | STUIX | × / √ | 1 Gbps | - |
| Seattle, US | AS36369 | - | √ / √ | 1 Gbps | - |
| Dallas, US | AS33696 | - | √ / √ | 1 Gbps | - |
| Vancouver, CA | AS53356 / AS6939 | UMETERED Exchange | √ / √ | 1 Gbps | - |
| Toronto, CA | AS835 / AS6939 | ONIX | √ / √ | 500 Mbps | - |
| Amsterdam, NL | AS34465 | INTERIX | √ / √ | 10 Gbps | - |
|  |  |  |  |  |  |


所有网络位置请查看 [Location]("./location/")
