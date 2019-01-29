# A Git Branching strategy test

## Outline
All branches will be by project stream and feature.

For instance - we have two project streams: project1 and project2.

There will be a specific development branch for both project1 and project2 each accepting their own PRs

Master            -------------------------------------------------------------------------------------- 
Development       --------------------------------------------------------------------------------------
Project1          --------------------------------------------------------------------------------------
Project1/feature1 --------------------------------------------------------------------------------------
Project2          --------------------------------------------------------------------------------------
Project2/feature2 --------------------------------------------------------------------------------------

Merges into master will be controlled by the technicalleads from the Project streams

Each project stream should be stable and will synchronize with master on occassion

When the project stream is stable, it will be merged into a development branch where full testing will be performed

Once the development branch is stable, we merge back into master for a stable release
