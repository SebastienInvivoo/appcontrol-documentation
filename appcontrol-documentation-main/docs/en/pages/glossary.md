# Glossary


## Element

| Name| Description|
| -----|--------------|
| COMPONENT |  Application, service or part of one |
| AGENT | Monitoring element of the component |
| GATEWAY | Gateway between the agent and the component |
| MAP | Set of relationships between components |
| OPERATION | Programmable action |

## Status App

| Name Status | Color |	Description |
|-------------|-------|---------------|
| Started | Green | It's fine |
| Degraded | Green-red | Partly active and partly not active |
| Not active | Black | Not Actived |
| Archived | Pink | Not active and retained |
| In error | Red | Error encountered |
| Starting | Yellow | In progress for Start |

## Status Component

| Name Status | Color |	Description |
|-------------|-------|---------------|
| Started | Green | It's fine |
| Stopped | Red | Manual stop |
| Not Active | Red | Non-manual stop |
| Agent Unreachable | Red | The agent cannot be found |
| Unknown | Gray | We do not know where the problem comes from |

## Status Agent ( work in progress)

| Name Status | Color |	Description |
|-------------|-------|---------------|
| Online | Green | Enabled and functional |
| Offline | Red | Disabled |
| Busy | X | Normally active but no response |
| Error | X | Return error |

## Status Gateaway ( work in progress)

| Name Status | Color |	Description |
|-------------|-------|---------------|
| Online | Green | Enabled and functional |
| Offline | Red | Disabled |
| Busy | X | Normally active but no response |
| Error | X | Return error |