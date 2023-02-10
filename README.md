# InnerSource Community Toolkit

When you are starting an InnerSource Community, you will need a toolkit to get your community off the ground quickly.
This is true no matter whether your community is a company-internal activity, a regional community, or a specific business-to-business sharing group.

Luckily this toolkit by the [InnerSource Commons](https://innersourcecommons.org) is just what you need to get your InnerSource community started. :)

## Existing communities

### Brazil

* Communication channel: Slack [#innersource-brazil channel](https://innersourcecommons.slack.com/archives/C03JP108XGE).
* Repository working directory: [Brazil](./brazil).
* Started in 2022.

### China

* Translations:
  * [InnerSource Learning Path](https://github.com/InnerSourceCommons/InnerSourceLearningPath/tree/main/introduction/zh) translations to Chinese.
  * [InnerSource Patterns](https://patterns.innersourcecommons.org/v/zh/) translations to Chinese.
* Started in 2022.

### France

* Communication channel: Slack [#fr-general channel](https://innersourcecommons.slack.com/archives/C04HJ3KPR19).
* Translations: [InnerSource Learning Path](https://github.com/InnerSourceCommons/InnerSourceLearningPath/tree/main/introduction/fr) translations to French.
* Repository working directory: [France](./france).
* Started in 2021.

### German Community

* Communication channel: Slack [#local-german channel](https://innersourcecommons.slack.com/archives/C016MNXK2MS).
* Translations: [InnerSource Learning Path](https://github.com/InnerSourceCommons/InnerSourceLearningPath/tree/main/introduction/de) translations to German.
* Started in 2020

### Italy

* Translations: [InnerSource Learning Path](https://github.com/InnerSourceCommons/InnerSourceLearningPath/tree/main/introduction/it) translations to Italian.
* Started in 2020.

### Japan

* Communication channels:
  * Slack [#jp-general channel](https://innersourcecommons.slack.com/archives/C03M546NR16) as main entry point for discussions.
  * Slack [#jp-marketing channel](https://innersourcecommons.slack.com/archives/C03N1QVR6FP) for marketing actions.
  * Slack [#jp-content channel](https://innersourcecommons.slack.com/archives/C03P1MVMBRS) for content-related discussions.
  * [Japanese Twitter account](https://twitter.com/InnerSourceJP).
* [Local in-person meetings](https://innersourcecommons.connpass.com/).
* Translations:
  * [InnerSource Learning Path](https://github.com/InnerSourceCommons/InnerSourceLearningPath/tree/main/introduction/ja) translations to Japanese.
  * [InnerSource Patterns](https://patterns.innersourcecommons.org/v/ja/) translations to Japanese.
  * [Getting Started with InnerSource Book](https://jp-contents.innersourcecommons.org/v/getting-started-with-innersource).
* Repository work:
  * Working directory: [Japan](./japan).
  * With the tag "**Japan :jp:**" you can filter for their [issues](https://github.com/InnerSourceCommons/community-toolkit/labels/Japan%20%3Ajp%3A) and [discussions](https://github.com/InnerSourceCommons/community-toolkit/discussions?discussions_q=label%3A%22Japan+%3Ajp%3A%22).
  * Their [Public Community Roadmap](https://github.com/orgs/InnerSourceCommons/projects/1) shows their plans for the coming quarters.
* Started in 2020.

### Russia

* Translations: [InnerSource Learning Path](https://github.com/InnerSourceCommons/InnerSourceLearningPath/tree/main/introduction/ru) translations to Russian.
* Started in 2021.

### Spain

* [Local in-person meetings](https://www.meetup.com/es-ES/innersource-spain/).
* Translations: [InnerSource Learning Path](https://github.com/InnerSourceCommons/InnerSourceLearningPath/tree/main/introduction/es) translations to Spanish.
* Started in 2018.

### Thailand

* Communication channel: Slack [#th-general channel](https://innersourcecommons.slack.com/archives/C04KNAD6S23).
* Repository working directory: [Thailand](./thailand).
* Started in 2022.


## How to create your community directory

Building on the structure of the [international](./international) directory is a good starting point.
You can customize the directory structure, but try to keep the base as close as possible so that other communities can easily refer to it.

The following commands may be helpful:

```sh
rsync -avz --include "*/" --exclude "*" international/ <YOUR_COMMUNITY_NAME>
find <YOUR_COMMUNITY_NAME>/ | xargs -I BASEPATH touch BASEPATH/.keep
```

## Questions?

This toolkit is really new!

Please contact us in [#local-community](https://innersourcecommons.slack.com/archives/C046MD5R5RT) in [Slack](https://innersourcecommons-inviter.herokuapp.com) with any questions.
