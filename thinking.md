Rumours

"Identity" rumour

  id: "rumour-mill"
  type: "service" | "entity" | "business-process" | or unspecified
  authority: "0.5" 

  git-path: "git:/kjldkjls"
  ... any key/value will be captured ...

  classes - service, team, business-process, 

"Connection" rumour

  class: "depends-on" | "part-of" | 
  source: "rumour-mill"
  target: "other-thing"

  for a dependency:
   data-flow: "pull" | "push" | "push+pull"