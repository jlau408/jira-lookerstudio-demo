# jira-lookerstudio-demo
This dashboard demonstrates how JIRA data can be integrated into Looker Studio for engineering metrics and delivery insights.

## Background
This dashboard demonstrates how JIRA data can be integrated into Looker Studio for engineering metrics and delivery insights. For the purposes of this demo, synthetic JIRA issue data was generated using the JetMock application, allowing realistic program and sprint analytics without exposing proprietary information.

### Executive Dashboard Overview
The first page provides a high-level view of all teams contributing to the program, with an optional filter to drill down into specific groups or projects. Key indicators include a four-week trend of newly opened defects and a priority distribution breakdown, enabling leadership to quickly assess overall product stability, emerging risk areas, and workload focus across teams.

### Screen Captures
1. Image of the Looker Studio overview page displaying four key charts summarizing performance across the three contributing teams. The visual highlights cross-team delivery trends, defect activity, and priority distribution at a glance.\
   \
   ![Image of the Looker Studio overview page displaying four key charts summarizing performance across the three contributing teams. The visual highlights cross-team delivery trends, defect activity, and priority distribution at a glance.](https://github.com/jlau408/jira-lookerstudio-demo/blob/main/images/Looker_Studio_Demo_JIRADashboard_Screenshot_20251205_ThreeTeams.png)

2. Image of the Looker Studio overview pages now filtered to two teams with updated four key performance charts.\
   \
   ![Image of the Looker Studio overview pages now filtered to two teams with updated four key performance charts.](https://github.com/jlau408/jira-lookerstudio-demo/blob/main/images/Looker_Studio_Demo_JIRADashboard_Screenshot_20251206_TwoTeams.png)
   
## Components:
1. **Atlassian JIRA**: [https://www.atlassian.com/software/jira]
2. **JetMock application**: [https://marketplace.atlassian.com/apps/1236711/jetmock-test-mock-data-generator-for-jira-sample-data]
3. **Looker Studio Connector for JIRA** (Tempo Software): [https://marketplace.atlassian.com/apps/1232588/looker-studio-connector-for-jira]
4. **Google Looker Studio**: [https://lookerstudio.google.com/]
