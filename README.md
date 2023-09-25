# tutorial-js-cypress
[![build workflow](https://github.com/Xray-App/tutorial-js-cypress/actions/workflows/main-cloud.yml/badge.svg)](https://github.com/Xray-App/tutorial-js-cypress/actions/workflows/main-cloud.yml)
[![license](https://img.shields.io/badge/License-BSD%203--Clause-green.svg)](https://opensource.org/licenses/BSD-3-Clause)
[![Gitter chat](https://badges.gitter.im/gitterHQ/gitter.png)](https://gitter.im/Xray-App/community)

## Overview
Code that supports the tutorial [Testing web applications using Cypress](https://docs.getxray.app/display/XRAYCLOUD/Testing+web+applications+using+Cypress) showcasing the integration between [Xray Test Management](https://www.getxray.app/) on Jira and Cypress, using JUnit XML reports.

The test automation code implements a basic [Cypress test](https://docs.cypress.io/guides/end-to-end-testing/writing-your-first-end-to-end-test).

## Prerequisites
In order to run this tutorial you need to have install the Cypress and have access to the [Cypress todo example](https://example.cypress.io/todo).

## Running
Tests can be executed locally with the following command
```
npx cypress run
```

## Submitting results to Jira

Results can be submitted to Jira so that they can be shared with the team and their impacts be easily analysed.
This can be achieved using [Xray Test Management](https://www.getxray.app/) as shown in further detail in this [tutorial for Xray Cloud](https://docs.getxray.app/display/XRAYCLOUD/Testing+web+applications+using+Cypress).

## Contact

Any questions related with this code, please raise issues in this GitHub project. Feel free to contribute and submit PR's.
For Xray specific questions, please contact [Xray's support team](https://jira.getxray.app/servicedesk/customer/portal/2).

## References

- [Writing Your First E2E Test tutorial by Cypress](https://docs.cypress.io/guides/end-to-end-testing/writing-your-first-end-to-end-test)
- [Cypress](https://cypress.io/)
- [How Xray processes JUnit XML reports](https://docs.getxray.app/display/XRAYCLOUD/Taking+advantage+of+JUnit+XML+reports)
- [Using Cypress JUnit reporter](https://docs.cypress.io/guides/tooling/reporters)
- [Cypress todo example](https://example.cypress.io/todo)


## LICENSE

[BSD 3-Clause](LICENSE)
