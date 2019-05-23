# Monitor, troubleshoot, and optimize solutions (10-15%)

## Develop code to support scalability of apps and services

- implement autoscaling rules and patterns (schedule, operational/system metrics, singleton applications)
  - <https://docs.microsoft.com/en-us/azure/azure-monitor/platform/autoscale-get-started>
- implement code that handles transient faults
  - <https://docs.microsoft.com/en-us/aspnet/aspnet/overview/developing-apps-with-windows-azure/building-real-world-cloud-apps-with-windows-azure/transient-fault-handling>

## Integrate caching and content delivery within solutions

- store and retrieve data in Azure Redis cache
  - <https://docs.microsoft.com/en-us/azure/azure-cache-for-redis/cache-dotnet-how-to-use-azure-redis-cache>
  - <https://docs.microsoft.com/en-us/azure/azure-cache-for-redis/cache-web-app-cache-aside-leaderboard>
- develop code to implement CDNs in solutions
  - <https://azure.microsoft.com/en-us/resources/samples/cdn-dotnet-manage-cdn/>
- invalidate cache content (CDN or Redis)
  - <https://docs.microsoft.com/en-us/azure/cdn/cdn-purge-endpoint>

## Instrument solutions to support monitoring and logging

- configure instrumentation in an app or service by using Application Insights
  - <https://docs.microsoft.com/en-us/azure/azure-monitor/app/cloudservices>
  - <https://docs.microsoft.com/en-us/azure/azure-monitor/app/asp-net>
- analyze and troubleshoot solutions by using Azure Monitor
  - <https://docs.microsoft.com/en-us/azure/azure-monitor/learn/tutorial-viewdata>
- implement Application Insights Web Test and Alerts
  - <https://azure.microsoft.com/en-us/blog/creating-a-web-test-alert-programmatically-with-application-insights/>
