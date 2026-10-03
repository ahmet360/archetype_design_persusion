# Team progress

[Project index](README.md) · [Work plan](WORK_PLAN.md) · [Current requirements](docs/CURRENT_REQUIREMENTS.md)

**Verified October 3, 2026, evening Eastern time.** This tracker separates submitted content, review, merge, assignment completion, fork sync, and Canvas submission. Work not present in main may exist in a member's local copy.

## Merged contributions

Ahmet authorized the merges in this chat. The files received an agent-assisted content review; automated Sourcery checks passed. This does not establish that another student performed the instructor-required peer review.

| Member | Merged work | PR and merge commit | Remaining work under the agreed allocation |
| --- | --- | --- | --- |
| Timothy Bailey | Explorer and Hero research drafts | [#7](https://github.com/ahmet360/archetype_design_persusion/pull/7), `18753225c2b4febda0c041fa16d5fb13b3ca3af8` | All eight research drafts now exist across main and open PRs: six pending topics covered by #15 and #16; definition sources, historical records, original designs, and peer review remain. Contribution/reflection file exists only in Tim's fork and is not in these PRs |
| Jeshan Ahmad | Innocent research; Creator-focused personal draft | [#3](https://github.com/ahmet360/archetype_design_persusion/pull/3), `802db148fe8a3941907c39c2978b57b000ae4889`; [#6](https://github.com/ahmet360/archetype_design_persusion/pull/6), `96f0b8acbb42458964f29d72d9c0653cb1c4a97d` | Jester, Creator, Ruler, De Stijl, Constructivism, Grunge Design, New Wave remain templates; correction submitted in #10 and About revision in #11, neither merged; original designs, accurate contribution statuses, peer review |
| Avyay Kaushik | All eight assigned research pages | [#4](https://github.com/ahmet360/archetype_design_persusion/pull/4), `d0d3dbfa4ad372a5a8aa0cd35714305243def275` | Two complete historical-example records per style, original archetype designs, About contribution record, peer review |
| Ahmet Elci | Management role reported handled; Issues enabled and these merges authorized | October 1 user instruction and verified GitHub merge results | Coordinate unresolved ownership, remaining reviews, fork sync, and confirmed handoff; no personal topic-writing backlog assigned here |

**11 of 31 topic files now contain merged research drafts**, plus one personal-page draft. This is not 11 completed deliverables. The seven persuasion pages remain templates without a newly agreed owner.

Tim's [PR #1](https://github.com/ahmet360/archetype_design_persusion/pull/1) was closed unmerged as redundant: its Explorer file is identical to the Explorer content merged through #7. Its wrong base branch is no longer a merge blocker. Jeshan's older #2 and #5 are also closed unmerged; #3 and #6 are the retained versions.

## New submissions awaiting management review

Main remains at `7b52af237e148c2b0ba4a9d1d1030bbcb3196f50` before this tracker update; no contribution merge has occurred since October 1. All 35 topic/member files are unchanged from the previous verified main. These new contributions are **submitted and agent-reviewed, not merged or complete**:

| PR | Owner and content | Verified head | Review result / next action |
| --- | --- | --- | --- |
| [#9](https://github.com/ahmet360/archetype_design_persusion/pull/9) | Tim — Outlaw research | `3f0a2d6dbd3974a1dc5a1663515653c1fab746cb` | Included unchanged in #12 and #13; no separate unique content |
| [#12](https://github.com/ahmet360/archetype_design_persusion/pull/12) | Tim — Outlaw + Sage research | `a4f00d85fb205907a4d78b4f5e62adb4621b583e` | Included unchanged in #13 |
| [#13](https://github.com/ahmet360/archetype_design_persusion/pull/13) | Tim — Outlaw + Sage + Bauhaus research | `edcd95efd6ce328e5f57b6ff82556ea026e4bb7a` | Review this cumulative PR; Outlaw needs an archetype-definition source, Bauhaus needs two documented historical works, and original archetype designs are absent |
| [#14](https://github.com/ahmet360/archetype_design_persusion/pull/14) | Tim — Outlaw + Sage + Bauhaus + Swiss Modernism | `05243c81bb88d8106863cf7316ae7d80b46af29c` | Four shared files also appear unchanged in both #15 and #16 |
| [#15](https://github.com/ahmet360/archetype_design_persusion/pull/15) | Tim — shared four files + Pop Art | `190d60c94a13fe46e370e54e84f193039846cc47` | Pop Art is unique to this PR; do not discard it when integrating #16 |
| [#16](https://github.com/ahmet360/archetype_design_persusion/pull/16) | Tim — shared four files + Memphis Design | `9877cfcf5544953867759e97c93448df4cf5b101` | Does not contain Pop Art; fix decorative-image guidance and designer spelling; complete historical-example records |
| [#10](https://github.com/ahmet360/archetype_design_persusion/pull/10) | Jeshan — Innocent section-name correction | `8cf209f54d969fd53c79c6fa58f0330a3eaaa796` | Changes “the full story” to “things we make,” matching the verified source; stale starter status remains |
| [#11](https://github.com/ahmet360/archetype_design_persusion/pull/11) | Jeshan — revised personal/About page | `57c126581b055d27ec296d1c7985d64bf8caa394` | Adds a real issue link, reflection, and font rationale; stale template status and missing per-contribution statuses remain |

The October 2 check found #9/#10/#11/#12/#13 clean and mergeable; their heads and review timestamps remain unchanged. On October 3, GitHub reports new #14/#15/#16 clean and mergeable with successful Sourcery check runs. Sourcery's review objects approve #14/#15, while #16 has approval pending for its decorative-image advice. A successful check is not proof that all content findings are fixed. No other-student review was verified.

Jeshan's #11 remains unchanged, including the earlier bot comment with approval pending. Its main finding refers to old progress text on the contributor branch: current group main already records #6's merge, and #11 only changes the member file. Do not overwrite the current tracker with old branch text.

The earlier Tim sequence runs #9 → #12 → #13 → #14, then splits into #15 (Pop Art) and #16 (Memphis). Both leaf PRs share the same four file blobs, but neither contains the other's final style page. Review #15 and #16 together and preserve both unique files if a later user-authorized merge proceeds. No PR was merged or closed during this check.

## Review follow-ups

- **Tim:** add a credible source for the Explorer, Hero, and Outlaw definitions; brand homepages alone do not establish the archetype framework. Sage now includes a framework citation, but its linked Guru page could not be retrieved by the web reader in this check, so accessibility/content was not verified. Bauhaus, Swiss Modernism, Pop Art, and Memphis each still lack two complete historical-work records. Pop Art names one Warhol work with a date, but does not supply the full institution/direct-source/credit record or a second work. Current website examples do not replace those records. Add the original archetype design examples separately.
- **Tim, Memphis #16:** use empty `alt=""` for purely decorative images or CSS backgrounds, reserving descriptive alt text for informative images, as explained by [W3C WAI](https://www.w3.org/WAI/tutorials/images/decorative/). Correct “Ettore Sotsass” to “Ettore Sottsass,” verified against [The Met's object record](https://www.metmuseum.org/art/collection/search/486989). These are verified findings, not merely copied bot suggestions.
- **Jeshan, Innocent:** [#10](https://github.com/ahmet360/archetype_design_persusion/pull/10) fixes the section name; [things we make](https://www.innocentdrinks.co.uk/things-we-make) was re-read and supports the quoted mission. The Sources section already links the direct page; linking it in the example paragraph would improve navigation. The starter-template status still needs updating. This correction is not yet in main.
- **Jeshan, member page:** [#11](https://github.com/ahmet360/archetype_design_persusion/pull/11) preserves his Creator choice, resolves the font “Pending” entry, and adds a reflection plus [a verified real issue in his fork](https://github.com/JeshanFAhmad/archetype_design_persusion/issues/4). Each contribution still needs an explicit status and a sentence describing his work; include the Innocent contribution too. Replace the stale “Template — awaiting ... interview” status. Main remains unchanged until a merge.
- **Avyay:** complete two historical-work records on each of Mid-Century Modern, Minimalist Modernism, Punk/Dadaist, and Retro-Futurism. Include creator, title, date, institution, direct source/viewing link, credits/reuse information, and a brief explanation. Shorten the 92-word NASA poster alternative and move extended analysis into a visible caption.
- **Team:** the merged archetype research pages do not yet contain the two original static hero designs required per archetype. These may be delivered in separate reviewed PRs. Instructor images under `assets/tutorial/` are not student designs.
- **Peer review:** no other-student approval was verified on these PRs. A bot check or agent review is not a student's contribution record.

The content review checked all substantive drafts and internal navigation. Some external sources and direct image fetches were unavailable; do not claim all external links or rendered images were verified.

## About files and issue tracking

Tim added [a completed-work/reflection file in his fork](https://github.com/Timothy-Bailey4-10/archetype_design_persusion/blob/cabb1863ae9d87d3442243425412145d70b3a9c8/timothy_completed_work_and_refelction.md). It accurately distinguishes work merged into his own fork from #7's group merge, but its claim that the topics are “Done” is a member report, not verified satisfaction of every assignment requirement. This file is not included in open group PR #15 or #16; Tim should submit it through a PR and reconcile it with his existing named About page, adding real issue links, introduction, and required contribution detail.

The [members folder](members/README.md) already contains a named file for each member. The October 1 assignment requires introduction, real issue links with contribution statuses, learning reflection, and credits. Earlier personal-archetype interviews are optional.

GitHub Issues were enabled October 1. Two open group issues are now present: Tim's [#17, definition citations](https://github.com/ahmet360/archetype_design_persusion/issues/17), and [#18, request to review and merge his work](https://github.com/ahmet360/archetype_design_persusion/issues/18). These are reports/requests, not proof that the citations were added or authority for this scheduled check to merge. Jeshan's linked fork issue #4 is real, open, and was created October 1. Its body uses a literal `(url)` Markdown target rather than the intended page URL; repair that issue link in the fork when possible. Record actual owners, reviewers, files, checklists, and contribution statuses; do not backdate issues or invent planning history.

## Fork synchronization

The instructor's main at `213f4308518789688bc2861744b9c1de45a179c3` is included by this synchronization merge. Current assignment, templates, optional tutorials, and original tutorial assets are preserved. Team research files and member writing are retained at their existing paths.

On October 3, **Jeshan's fork main exactly matched group main** at `7b52af237e148c2b0ba4a9d1d1030bbcb3196f50`, before this tracker update.

Tim's fork main contains all group commits plus eight additional commits. Six populate the pending research topics and two add/update his contribution/reflection file. The six topic-file blobs match his group PR submissions. His fork head is `cabb1863ae9d87d3442243425412145d70b3a9c8`; its additions are not merged into the group merely because he integrated them in his fork.

Avyay's fork main still lacks substantive group updates (48 commits behind at this check). The connected account cannot push to teammates' forks. Avyay must sync from group main; after contribution merges, contributors should sync again. Do not force-reset Tim's extra work. A tracker-only commit does not invalidate verified synchronization of substantive work. Follow [CONTRIBUTING.md](CONTRIBUTING.md#sync-your-fork-after-group-merges).

## Member reports and communication

In the SMS conversation “Is117 group project,” Jeshan reported his Innocent submission September 30 and asked that patch 2 be used; Avyay reported his submission that night. Tim reported additional work planned October 1 and asked for named contribution files, the instructor update, and a merge notice. The newer PR evidence above supersedes older reports that only Explorer existed or Jeshan's personal page was still unsubmitted.

Ahmet posted the revised design and About-page requirements in the group on October 1 at 5:26 PM Eastern. Timothy acknowledged them at 5:28 PM. The October 3 read again found no newer messages in that group conversation. Tim's new progress and merge request were found in GitHub PRs, his fork, and issues #17/#18.

Last automated reminder verified sent: **September 30 at 6:04 PM Eastern**. No messages were sent during the October 1, October 2, or October 3 checks. Ahmet requested reply drafts to send himself.

## Deadline and handoff

Re-read [Canvas Part 1](https://njit.instructure.com/courses/70711/assignments/761949) on October 3: it still lists **October 2, 2026, at 11:59 PM Eastern**, website URL submission, and says each member submits their own fork updated to match the leader. The visible action remains “Start Assignment”; no submission receipt was observed. The displayed deadline has passed, but no claim is made about a teammate's personal Canvas status.

The instructor main remains at `213f4308518789688bc2861744b9c1de45a179c3`, whose assignment says the lead submits. Confirm any newer instructor arrangement and the submission route. Canvas does not separately enumerate which project stages its Part 1 label covers; do not invent that scope.

Management next steps: respond to Tim's merge request with the required corrections; preserve the unique pages in both #15 and #16; obtain a PR for his fork-only reflection; review Jeshan #10/#11; coordinate Avyay's sync; and verify Canvas receipt/status. Seven persuasion pages still need agreed ownership; no new owner is assigned here.

No final Canvas receipt or final coursework completion is asserted. Ahmet's report that his manager role is handled is not a submission receipt. No merges, collaborator additions, coursework submissions, or external messages were performed by this check.
