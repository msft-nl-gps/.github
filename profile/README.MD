# ALZ high level deployment flow
1. Management Groups and Subscriptions handling module
2. Custom Policy definitions module
3. Creation and deployment of Custom RBAC Role Definitions module
4. Policy assignment module (assign subset)
5. Logging & Security module
6. MGs Diagnostic Settings orchestration (optional)
7. Policy assignment module (assign subset)
8. Network vwanConnectivity module
9. Network spokeNetworking module
10. Network vnetPeeringVwan module
11. Policy assignment module (assign subset)

![Intial state](https://raw.githubusercontent.com/msft-azure-iac-hackathon/.github/main/profile/ALZ-0.png)
![Managment groups and Subscriptions](https://raw.githubusercontent.com/msft-azure-iac-hackathon/.github/main/profile/ALZ-1.png)
![Custom Policy definitions](https://raw.githubusercontent.com/msft-azure-iac-hackathon/.github/main/profile/ALZ-2.png)
![Custom RBAC](https://raw.githubusercontent.com/msft-azure-iac-hackathon/.github/main/profile/ALZ-3.png)
![Custom Policy assignment](https://raw.githubusercontent.com/msft-azure-iac-hackathon/.github/main/profile/ALZ-4.png)
![Logging and Security](https://raw.githubusercontent.com/msft-azure-iac-hackathon/.github/main/profile/ALZ-5.png)
![MG Diagnostics](https://raw.githubusercontent.com/msft-azure-iac-hackathon/.github/main/profile/ALZ-6.png)
![Custom Policy assignment](https://raw.githubusercontent.com/msft-azure-iac-hackathon/.github/main/profile/ALZ-7.png)
![Network](https://raw.githubusercontent.com/msft-azure-iac-hackathon/.github/main/profile/ALZ-8-10.png)
![Custom Policy assignment](https://raw.githubusercontent.com/msft-azure-iac-hackathon/.github/main/profile/ALZ-11.png)


# Logistics
## Granting access:
Using event registration email addresses (no dedicated creds)

## Azure subscriptions:
https://portal.azure.com

## Azure Directory name:
Tatooine

## GitHub Organization for this event:
https://github.com/msft-azure-iac-hackathon

## Bicep modules:
https://aka.ms/ALZ/bicep

## GitHub actions and its runners
https://github.com/msft-azure-iac-hackathon/github-runner-in-azure-container-apps 

# Daily program
## Day 1

| Timeslot | Subject | Details | Session type |
|:--------:|-------|-----------|------|
|09:00 - 09:30|Introductions & Goals|The why|Keynote|
|09:30 - 10:00|Agenda & Logistics|The how|General|
|10:00 - 11:00|Kickoff| <ul><li>Short introduction into AZL</li><li>How to work with the AZL repos</li><li>Which solution will land on the AZL</li><li>Hands-on</li></ul>|General|
|11:00 - 11:10|Break||Break|
|11:10 - 12:00|Hands-on|Design, parameterize and deploy your Azure Landing Zone from GitHub Workflows|Hands-on/lab|
|12:00 - 13:00|Lunch break||Break|
|13:00 - 17:00|Hands-on|Continue the landing zone deployment|Hands-on/lab|

## Day 2

| Timeslot | Subject | Details | Session type |
|:--------:|-------|-----------|------|
|09:00 - 09:30|Day refresher|Recap of yesterday & leasons learned|General|
|09:30 - 12:00|Hands-on|Continue the Landing Zone deployments (breaks as needed)|Hands-on/lab|
|12:00 - 13:00|Lunch break||Break|
|13:00 - 14:00|Solution Automation|Learn about a new solution that you must deploy on top of your ESLZ. You will need to build your own templates and pipelines.|Brainstorming|
|14:00 - 17:00|Hands-on|Start deploying your custom solution (breaks as needed)|Hands-on/lab|

## Day 3

| Timeslot | Subject | Details | Session type |
|:--------:|-------|-----------|------|
|09:00 - 09:30|Day refresher|Recap of yesterday & leasons learned|General|
|09:30 - 12:00|Hands-on|Continue the rollout of your custom solution (breaks as needed)|Hands-on/lab|
|12:00 - 13:00|Lunch break||Break|
|13:00 - 13:30|Next steps|How to share this knowledge and experience within your organization|Keynote|
|13:30 - 17:00|Hands-on|Continue the rollout of your custom solution (breaks as needed)|Hands-on/lab|
