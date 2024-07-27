# Enterpret-assignment

## Live Link : https://enterpretassignment.web.app/

Assignment for frontend intern

### Tech Stack

-   Next.js
-   Tailwind CSS
-   Typescript

### Installation

Install the dependencies, build and start the server.

```
npm i
npm run build
npm start
```

### About

`index.tsx` is the main entrypoint. It's has two main component sidebar and query container. Siderbar has build query button when clicked open create query modal where you can create the queries, and query container will render list of all the queries created.

### Rule Group

*Not much information is provided on how to convert rule object to string
and how rule group is connected to other rule group.
I tried to ask for sample queries but didn't get any response.*

So based on my understanding I structured in a way like:
the output of each query will be a rule_group and a rule_group can a have a array of rules or rule_groups as children. A rule is filter object that has some condition to be fulfilled.

Each rule will be joined based on the conjuction provided, and rules when combined will form bigger rule group.

