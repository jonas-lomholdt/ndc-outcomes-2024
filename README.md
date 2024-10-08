# ndc-outcomes-2024
Key outcomes from NDC Developers Festival 2024

## Building Secure ReactJS Applications: Mastering Advanced Security Techniques
> YouTube version https://www.youtube.com/watch?v=PyLE8ujGQMg of the same talk but from last year. It changed a little bit, but much of the same content.

In general frontend frameworks will help you most of the way, but there are many ways to circumvent the inbuilt security if not handled properly.

- There's an [ESLint plugin](https://www.npmjs.com/package/eslint-plugin-security) that will find many of the common security mistakes and highlight them if they happen
- Don't have Admin related UI together with none admin, have a separate UI specifically for Admin related actions.

## Exposing the not-so-secret practices of the cult of DDD
- Name repository interfaces as eg. `IUser` omitting the "Repository" suffix
- Name repository methods eg. as `ThatLivesIn(City("Copenhagen"));` instead of eg. `WithCity` so it reads out well. That would make it read `var users = users.ThatLivesIn(new City("Copenhagen"))`


## Looks GREAT To Me: Getting Past Bare Minimum Code Reviews (https://www.youtube.com/watch?v=1FdcIvfSi_A)
A talk on the key concepts from her book [Looks Good to me](https://www.manning.com/books/looks-good-to-me) where she talks about do's and dont's in PR.
- Remember to state the
- A PR review can take up to 45 min
- Don't do large PR's (eg. +50 file changes)
- Include a good description so the reviewer doesn't have to start digging to understand what's going on
- Don't nitpick, and if you do, keep it at a minimum
- Tripple R Pattern: Request, Rationale, Result
