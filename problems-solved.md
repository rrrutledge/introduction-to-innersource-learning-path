This file holds the text to accompany the [What Problems Does InnerSource Solve?](https://www.safaribooksonline.com/videos/introduction-to-innersource/9781492041504/9781492041504-video321607) video.

# What Problems Does InnerSource Solve?

To illustrate the types of situations where inner source can help, imagine the following.
Suppose two teams at the same company deliver separate pieces of software with one team's software depending on that of the other.
An example could be a user experience that depends on an API service to retrieve data for display.
This situation is common in a large enterprise where a single team producing software may have dozens or hundreds of consumers.

When consuming teams need many features, producing teams normally have some sort of requirements and prioritization process to decide which features they will work on.
For critical feature requests that are not prioritized for immediate work, the consuming team may commonly choose one of 3 options, each of which come with their own drawbacks.

  1. **Wait it out**. The consuming team may do nothing and limp along without the requested functionality.
  This option requires the least amount of work on their side.
  Depending on the benefit of the feature request, waiting might be just fine.
  However, it may come with real amounts of pain, especially if the requested functionalty is never delivered.
  1. **Workaround**. A consuming team that doesn't want to wait may do extra work somewhere else to compensate for the absence of their requested feature.
  This extra work may come as change in the consuming project.
  Alternatively, they may create a new project that meets their needs and replaces their use of all or part of the producing team's system (code/project duplication).
  This strategy allows the consuming team to get the requested feature via their own efforts only (no hard dependencies). It comes with several drawbacks, though.
      
      1. Any work done by the consuming team remains unavailable to any other consumers with the same feature request.
      1. The consuming team has inadvertently signed up for the long-term burden of maintaining the newly-written code, which is not in the domain of their core team competency.
      1. The company as-a-whole acquires duplicate projects and code in the same problem space.
      
  1. **Escalate**. The consuming team may not take "no" for an answer and, instead, advocate to someone in the producers' management hierarchy to influence (or force) the producing team to do the work.
  This option sounds attractive for the consuming team because they get the requested feature without doing the work to implement or maintain it.
  It is still a drag on the team, though, because it necessarily diverts some of their attention and work to the non-engineering task of escalation.
  Additionally, this option does not scale as there are so many times that a consumer can escalate feature requests before damaging their credibility.
  Escalate is similarly disruptive (even more so) for the producing team, who are taken out of their normal workflow and prioritization methods to deal with the escalated feature request.

This discussion sets the stage for inner source.
Inner source applies to the same type of situation where a consuming team is unable to get what needs via feature request.
Inner source provides a way for the teams to gain the benefits of _wait it out_, _workaround_, and _escalate_ without the associated drawbacks.
