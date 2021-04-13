# Kadaster FDP Local Deployment Configuration

This is an example production deployment of Kadasters FDP instance. It contains images from [FAIR Data Point](https://fairdatapoint.readthedocs.io/) (FDP) and mock implementations of service extensions. This repository serves only to display configuration required for production deployment, particularly the nginx setup. 

## Project Architecture

The following illustrates the overall architecture of this project in the Kadaster context. In practice, the architecture includes 5 services:

1. Metadata Provider Service
2. FAIR Data Accessor Service
3. SHACL Validator Service
4. Client Interface Service
5. Triple Store Interface Service

Figure 1: Project Architecture in Kadaster's Context
![image](https://user-images.githubusercontent.com/74549995/114614386-b9c1fd80-9ca4-11eb-907a-a12ec5976138.png)

## Important notes

For more information on the overall vision for the FDP, see [FDP Docs](https://fairdatapoint.readthedocs.io/)

