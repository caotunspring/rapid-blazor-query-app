# rapid-blazor-query-app 快速建構 Blazor 查詢 APP

### Ref
- https://paulcunningham.me/writing-technical-books/
> Blazor Server 取代傳統 Web Forms
> EF Core 取代傳統 EF 6

## 本書重點
- 在現有數據庫的基礎上,將選定的 Table/View 生成 Blazor 頁面
- 使用 NuGet 上的 Package, 快速建立標準可配置的查詢頁面
- 使用JSON調試各頁面篩選排序分頁等功能
- 有立即可用的開源代碼, 可以針對個別需求自行擴展二次開發

## 前言
2020年我個人參與了倉儲相關的項目, Codebase 約十年前起創, C#, 團隊使用VS2012, 項目的主體使用 Web Forms, 數據庫是微軟的 MS SQL, 代碼存取數據庫混用 EF 6 和 Drapper, 版本控制採用 SVN。
參與項目的前中後, 密切觀察和試用 .NET 相關的技術。
直接講結論, "Blazor Server 取代傳統 Web Forms,EF Core 取代傳統 EF 6"

## 第一章 從官網的範例走起
- 取得官網範例代碼
- 運行範例代碼
- 體驗App功能
- 查看代碼
- 更換數據庫
- 存取數據庫的方式
  
## 第二章 直接使用本書的開發模式
- 新建項目調整Nav
- EF Core Power Tool
- 下載 NuGet Package
- 繼承 AppCompBase
- 運行並調試頁面

## 第三章 介紹項目主要組成
- Blazor Base
## 第四章 介紹所使用的 NuGet Package
- Wrapper
- SearchComp
- TableComp
- PagingComp
- Adapter
- Filter
- PageHelper

## 第五章 擴展方向及範例
- 規畫篩選的欄位
- 限定排序的欄位
- Html Table 的顯示
- 分頁的顯示




