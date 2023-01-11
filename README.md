
# k6-executors                                ![download](https://user-images.githubusercontent.com/93552647/152650021-b0f0a5a9-f778-4acf-a69b-d17eaa54f713.png)

This repo we have implemented the several types of executors provide by K6 with html report. 

## Executors Types

#### 1. Shared iterations:	A fixed amount of iterations are "shared" between a number of VUs.

#### 2. Per VU iterations	per-vu-iterations	Each VU executes an exact number of iterations.

#### 3. Constant VUs	constant-vus	A fixed number of VUs execute as many iterations as possible for a specified amount of time.

#### 4. Ramping VUs	ramping-vus	A variable number of VUs execute as many iterations as possible for a specified amount of time.

#### 5. Constant Arrival Rate	constant-arrival-rate	A fixed number of iterations are executed in a specified period of time.

#### 6. Ramping Arrival Rate	ramping-arrival-rate	A variable number of iterations are executed in a specified period of time.

#### 7. Externally Controlled	externally-controlled	Control and scale execution at runtime via k6's REST API or the CLI.

## For more details:
About the executors can see this link : https://k6.io/docs/using-k6/scenarios/executors/

## Tip:


The mainly goal we can achieve using Executor is the facility we have to set some especific performance techniques, like **constant-arrival-rate** can use endurance test approach through the engine instead of to write manually like this example: https://k6.io/docs/test-types/soak-testing/.
