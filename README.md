

# New Staff Guide

When you are a new staff in the HK01-development and if you don`t known what you should to do in the beginning, then you may need the guide.

<a name="Overview"></a>

## Overview

- Tech Stack List
- Dev Accounts
- Dev Tools
- Common Words
- Other Guides

<a name="43c737f9"></a>

## Tech Stack List

The list can make you known what`s the main tech stacks in our projects quickly, you also can find the all stacks in the **package.json**.

<a name="Language"></a>

### Language

- [TypeScript](http://www.typescriptlang.org/) A language for application-scale JavaScript.

<a name="FrameWork"></a>

### FrameWork

- [React](https://reactjs.org/) - A JavaScript library for building user interfaces
- [Next.js](https://nextjs.org/) - Server-Side Rendering framework of React
- [Express](https://expressjs.com/) - Node.js web application framework
- [Jest](https://jestjs.io/) - A delightful JavaScript Testing Framework

<a name="94bc75cb"></a>

### Library/Components

- [ramda.js](https://ramdajs.com/) - A practical functional library for JavaScript programmers.
- [Redux](https://redux.js.org/) - A predictable state container for JavaScript apps
- [React-reudx](https://react-redux.js.org/) - Official React bindings for Redux
- [Redux-saga](https://redux-saga.js.org/) - Redux middleware
- [styled-components](https://www.styled-components.com/) - Use the best bits of ES6 and CSS to style your apps without stress
- [ant-design](https://ant.design/docs/react/introduce-cn) - React UI library
- [@rebass/grid](https://rebassjs.org/guides) - React primitive UI components built with Styled System

<a name="0bbaae07"></a>

### Dev Tool/Service

- [Webpack](https://webpack.js.org/) - Static module bundler for JavaScript applications
- [Travis](https://travis-ci.org/) - A test and deploy tool sync GitHub projects
- [Docker](https://www.docker.com/) - Securely build, share and run modern applications anywhere

<a name="Tools"></a>

## Tools

You need to log in the follow platforms by **Gmail Count** in your work, please ask for the key before start your develop

- [Gmail](http://mail.google.com) - the email account is the **key** access all our production
- [Github](https://github.com/) - The world's leading software **development** platform
- [Bitwarden](https://ops-bitwarden.wezeroplus.com/#/) - where you can get the **npm token** and other tool`s  **account** and **password**
- [Slack](https://slack.com) - A collaboration Tool, work chat and receive development message.
- [Swagger](https://swagger.io/) - A api tool
- [Zeplin](https://zeplin.io/) A collaboration tool for designer and development
- [JIRA](https://www.atlassian.com) - Software development tool used by agile teams

<a name="a2f96d5e"></a>

## Common Words

In a large system, the common words are very necessary to exist, it can be the feature of the product, it`s also can help to communicate with others and translate the requirements of each module or system into an executable process.

- **Ticket** - JIRA`s Issues.
- **LGTM** - Look Good To Me.
- **CC** - Carbon Copy
- **Channel** - The Slack Channel.
- **DCE** - Website for District Council Elections 2019
- **PMP** - Partner Management Panel
- **PGC** - Professional Generated Content
- **UGC** - User Generated Content
- **BGC** - Business Generated Content 
- **ETA** - Estimated Time of Arrival
- **TBC**- To Be Continue

[https://docs.google.com/document/d/1x-bl69_jnZoFUUOUtDAUByZv2oXT8ps2ITa3BO1lNuY/edit#heading=h.r9ifey90d5m2](https://docs.google.com/document/d/1x-bl69_jnZoFUUOUtDAUByZv2oXT8ps2ITa3BO1lNuY/edit#heading=h.r9ifey90d5m2)

<a name="58aad38d"></a>

## Other Guides

You can read the follow guides when you need remote option

- DCE Deploy Guide
- what`s you should do when you PR and CR.
- What`s you need pay attention to in your work.

<a name="FQA"></a>

## FQA

<a name="8b5417e0"></a>

### You don`t have access of Github repo or other tools?

Please [@devops ]() in `#ask-devops` channel, you can send message as follow:

> @devops, hi, please helo to gant access of ${tool-name}, thank you! ETA: ${date} .cc@{$need cc people}


<a name="5e1ac5d0"></a>

### What`s the time to delete release branches?

At least has **four** release branches, you can delete them in Github branches. If your **release** branch is **protected**, please [@devops ]() in '#ask-devops' channel, you can send message as follow:

> @devops please help to remove all the release/* branches in ${repo-name} ETA: ${date}, thank you

