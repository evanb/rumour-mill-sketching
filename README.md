Kicking around the format for a feed of rumours

## "Identity" rumour

    id: "rumour-mill"
    type: "service" | "entity" | "business-process" | or unspecified
    authority: "0.5" 

    git-path: "git:/kjldkjls"
    ... any key/value will be captured ...

  types - service, team, business-process, 

## "Connection" rumour

    type: "depends-on" | "part-of" | "owned-by"
    source: "rumour-mill"
    target: "other-thing"
    authority: "0.8"

  for a dependency:

    data-flow: "pull" | "push" | "push+pull"