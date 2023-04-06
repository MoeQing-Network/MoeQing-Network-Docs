## 可直接提供 Transit 的位置
通常情况下支持的连接类型：

**隧道：** `SIT` / `WireGuard` （**不支持 ZeroTier！**）

**物理：** `IX LAN` / 主机商提供的 `VLAN` 或 `Private Network`

申请 Transit： [填写 Google 表单](https://docs.google.com/forms/d/1SasEOAeSqNKDwfeY1-lgq1L020n0V3ashHsIe--elhk)



> 除此之外的所有位置均可提供 Transit，但因没有当地上游，延迟会增加。
> 
> 所有网络位置请查看 [Location](./location.md)
### 与 Tier 1/2 ISP 建立连接的位置
| Location | Upstream | IXP | v4 / v6 | Speed |
| :----: | :----: | :----: | :----: | :----: |
| Taipei | AS6939 | STUIX | × / √ | 1 Gbps |
| Singapore | AS8849 | - | × / √ | 10 Gbps |
| Seattle, US | AS36369 | MoeIX SEA | √ / √ | 1 Gbps |
| Los Angeles, US | AS8849 | - | × / √ | 10 Gbps |
| Los Angeles 2, US | AS202888* | - | √ / √ | 1 Gbps |
| Fremont, US | AS6939 | Lambda-IX  | × / √ | 1 Gbps |
| Kansas City, US | AS6939 | GPC Missouri  | × / √ | 1 Gbps |
| Vancouver, CA | AS53356 / AS6939 | UMETERED Exchange | √ / √ | 1 Gbps |
| Amsterdam, NL | AS34465 | INTERIX | √ / √ | 10 Gbps |
| Moscow, RU | AS56630 | - | × / √ | 10 Gbps |
| Frankfurt 2, DE | AS6939 / AS34927* | LocIX / FogIX | × / √ | 1 Gbps |

`*` 为需要 `LOA` 或 `上游添加白名单` 的 upstream

### 与 Tier 3 ISP 或 其他类型 ISP 建立连接的位置
| Location | Upstream | IXP | v4 / v6 | Speed |
| :----: | :----: | :----: | :----: | :----: |
| Fremont 2, US | AS206628 | - | × / √ | 1 Gbps |



