# doc-snippets CLI (v1)
## Goals
* Create a `doc-snippets` CLI tool, that enables the embedding of code snippets in our documentation files (markdown, etc).
* Use the `doc-snippets` CLI within the `polywrap/documentation` repo.
* Publish `doc-snippets` as a standalone CLI, so it can be used as a general utility for any project.

## Non-Goals
* Verifying that the code snippets being injected are correct (buildable) can be done separately.
* This CLI will be first created as a Node.js based application. In the future it can be built as a wrapper, and run using the `pwr` CLI.

## Duration
1 Month: 10/01/22 - 11/01/22

## Leadership & Contributors
[@pileks](https://github.com/pileks) - Jure G has been a member of the Polywrap DAO for ~5 months now, originally voted in as a committed contributor [on August 15th](https://snapshot.org/#/polywrap.eth/proposal/0x8ba0965670fca9e6b2e8349d82b7ff146a1fefd283cb4e9a4967d78600cda040).

Other Contributors:
  * [@krisbitney](https://github.com/krisbitney) - Helping review PRs, and integrate the CLI into the documentation repo.
  * [@dorgjelli](https://github.com/dorgjelli) - Providing feedback on the CLI, as it is based on a set of scripts @dorgjelli had created prior.

## Context
The documentation repo already has scripts custom built for it, that embed code snippets into the docs. We (pileks, krisbitney, dorgjelli) would like to bundle this "code snippet embedding" logic into a useful CLI, such that we can use it in other repos (not just documentation).

This work has already been prioritized & scheduled within the [Docs Roadmap](https://github.com/orgs/polywrap/projects/6/views/17).

## Impact
Firstly, this is targeting internal use to help us create more robust documentation for the Polywrap toolchain.  

Secondly, we have noticed that another CLI like this does not exist, and imagine other in the general developer community could make use of the CLI.

## Progress Updates
All source code for this project will be developed here:  
https://github.com/polywrap/doc-snippets

Tracking Issue:  
https://github.com/polywrap/documentation/issues/232

### Midpoint Checkpoint (10/15/22)
We conduced a midpoint checkpoint today with @pileks, @dorgjelli, @krisbitney, @namesty, and @emmadsharma. Overall progress is good and on-track for completion by the 1 month timeframe.

## Submission
Published CLI on NPM:  
https://www.npmjs.com/package/doc-snippets

Integration Into Documentation Repo: 
https://github.com/polywrap/documentation/blob/dcd5720f07312683a155e95d0bcf2922cc420174/package.json#L20

## Demo & Retro
[Demo](https://youtu.be/dQw4w9WgXcQ)  
[Retrospective](https://youtu.be/mLyOj_QD4a4)  
