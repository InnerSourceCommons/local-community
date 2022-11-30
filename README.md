# InnerSource Community Toolkit

If you are starting an Innersource Community, whether it is an internal activity, a region-specific community, or a specific business-to-business sharing group, you will need a toolkit. Fortunately, InnerSource Commons has them. This toolkit is just what you need to get started in your inner source community.

## How to create your community directory

Building on the structure of the international directory is a good first starting point.
You can customize the directory structure, but try to keep the base as close as possible so that other communities can easily refer to it.

The following commands may be helpful

```sh
rsync -avz --include "*/" --exclude "*" international/ <YOUR_COMMUNITY_NAME>
find <YOUR_COMMUNITY_NAME>/ | xargs -I BASEPATH touch BASEPATH/.keep
```
