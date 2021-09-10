# nextjs-multi-zones-with-docker

This is a base structure of project in NextJS for to plan a migration between existents project, legacy and new.

![alt text](https://raw.githubusercontent.com/henriqueweiand/nextjs-multi-zones-with-docker/master/assets/plan.png)

The main way for to solve is using https://nextjs.org/docs/advanced-features/multi-zones, but sometimes the effort is bigger than this alternative.

## POC: validation strategy

Case 1:

- Run two nextjs projects;
- Run proxy and tests access between projects;
- Add and test if the session/cookies working across projects;

Case 2:

- The same itens of case 1;
- Write a strategy for routes between projects;
