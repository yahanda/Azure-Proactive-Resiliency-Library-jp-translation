+++
title = "Application Insights"
description = "Best practices and resiliency recommendations for Application Insights and associated resources and settings."
date = "10/4/23"
author = "onderyildirim"
msAuthor = "ondery"
draft = false
+++

The presented resiliency recommendations in this guidance include Application Insights and associated resources and settings.

## Summary of Recommendations

The below table shows the list of resiliency recommendations for Application Insights and associated resources.

{{< table style="table-striped" >}}
| Recommendation                                    |  Category                                                               |  Impact         |  State            | ARG Query Available |
| :------------------------------------------------ | :---------------------------------------------------------------------: | :------:        | :------:          | :-----------------: |
| [APPI-1 - Convert Classic Deployments](#appi-1---convert-classic-deployments) | Availability | Medium | Preview  |         Yes         |
{{< /table >}}

{{< alert style="info" >}}

Definitions of states can be found [here]({{< ref "../../../_index.md#definitions-of-terms-used-in-aprl">}})

{{< /alert >}}

## Recommendations Details

### APPI-1 - クラシックデプロイを変換します

**Category: Availability**

**Impact: Medium**

**Recommendation**

クラシック Application Insights は 2024 年 2 月に廃止されます。既存のアプリケーション監視シナリオの中断を最小限に抑えるには、2024 年 2 月 29 日までにワークスペースベースの Application Insights に移行してください。

**Resources**

- [Migrate an Application Insights classic resource to a workspace-based resource](https://learn.microsoft.com/ja-jp/azure/azure-monitor/app/convert-classic-resource)

**Resource Graph Query**

{{< collapse title="Show/Hide Query/Script" >}}

{{< code lang="sql" file="code/appi-1/appi-1.kql" >}} {{< /code >}}

{{< /collapse >}}

<br><br>

