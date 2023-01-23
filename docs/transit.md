## 可直接提供 Transit 的位置
通常情况下支持的连接类型：

**隧道：** `SIT` / `WireGuard` （**不支持 ZeroTier！**）

**物理：** `IX LAN` / 主机商提供的 `VLAN`

申请 Transit： [填写 Google 表单](https://docs.google.com/forms/d/1SasEOAeSqNKDwfeY1-lgq1L020n0V3ashHsIe--elhk)



> 除此之外的所有位置均可提供 Transit，但因没有当地上游，延迟会增加。
> 
> 所有网络位置请查看 [Location](./location.md)
### 与 Tier 1/2 ISP 建立连接的位置
| Location | Upstream | IXP | v4 / v6 | Speed | Looking Glass | 
| :----: | :----: | :----: | :----: | :----: | :----: |
| Taipei | AS6939 | STUIX | × / √ | 1 Gbps | - |
| Seattle, US | AS36369 | MoeIX SEA | √ / √ | 1 Gbps | - |
| Vancouver, CA | AS53356 / AS6939 | UMETERED Exchange | √ / √ | 1 Gbps | - |
| Toronto, CA | AS835 / AS6939 | ONIX | √ / √ | 500 Mbps | - |
| Amsterdam, NL | AS34465 | INTERIX | √ / √ | 10 Gbps | - |

### 与 Tier 3 ISP 或 其他类型 ISP 建立连接的位置
| Location | Upstream | IXP | v4 / v6 | Speed | Looking Glass | 
| :----: | :----: | :----: | :----: | :----: | :----: |
| Dallas, US | AS33696 | - | √ / √ | 1 Gbps | - |
| Fremont, US | AS206628 | - | × / √ | 1 Gbps | - |
| Frankfurt, DE | AS134478 | - | × / √ | 1 Gbps | - |
| Moscow, RU | AS206016 | - | × / √ | 1 Gbps | - |




## 可提供 Transit 但需要 `LOA` 或 `上游添加白名单` 的位置
| Location | Upstream | IXP | v4 / v6 | Speed | Looking Glass | 
| :----: | :----: | :----: | :----: | :----: | :----: |
| Los Angeles, US | AS202888 | - | √ / √ | 1 Gbps | - |
