# Natural Language Processing Course

>_This page is auto-generated - do not edit; manual edits are overwritten on the next refresh._

This is the dedicated **Natural Language Processing** **course org** - persistent across years. It acts as:
1. A **private staging area** for pre-release version-controlled materials & assignments,
2. A **historical record** of past years' materials,
3. A **central control panel** for instructors to run workflows from, via the seeded [`.github` Actions tab](https://github.com/hertie-nlp-e1282/.github/actions).

The substantive repos of this org are private (not accessible to enrolled students); each year's student-facing interface lives in a separate **semester org** that receives releases from here.

> **Faculty & instructors - start here:** New to the platform?
> Follow the step-by-step
> **[workflow runbooks](https://github.com/hertie-data-science-lab/dsl-teaching-toolkit/blob/release/docs/README.md)**.
> The sections below are a live index of this org's semesters, repositories, and actions.

## Semesters

List of semester orgs registered to receive releases from this course org. _Auto-discovered from the
`semesters.yml` registry_:

- [hertie-nlp-f2026](https://github.com/hertie-nlp-f2026)

## Repositories

List of all repositories associated with the course org. _Auto-discovered from the org's live repositories_.

| Repo | Visibility | Description |
| --- | --- | --- |
| [assignment-1-f2026](https://github.com/hertie-nlp-e1282/assignment-1-f2026) | private | Assignment 1: Quiz 1 |
| [course-materials-f2026](https://github.com/hertie-nlp-e1282/course-materials-f2026) | private | Course materials (lectures/labs/readings/datasets/other) by session |

Edit & stage new course-related content in these, then release it to the relevant semester org.

## What you can do

Every operation below is a button in the Instructor Console and the same request from a
laptop: `python -m dsl_course <op>` in a checkout of the
[toolkit](https://github.com/hertie-data-science-lab/dsl-teaching-toolkit), with `gh` signed in. A command previews unless
given `--no-preview`; `python -m dsl_course <op> --help` lists its `--arg`s.

| Operation | What it does | Console | Command |
| --- | --- | --- | --- |
| `semester.check` | Check the semester's setup and refresh what the console shows. | [Console](https://hertie-data-science-lab.github.io/dsl-teaching-toolkit/) | `python -m dsl_course semester.check --course-org hertie-nlp-e1282 --semester-org <semester-org>` |
| `semester.preview_automation` | Preview what automation would release in this semester now. | [Console](https://hertie-data-science-lab.github.io/dsl-teaching-toolkit/) | `python -m dsl_course semester.preview_automation --course-org hertie-nlp-e1282 --semester-org <semester-org>` |
| `release.entry` | Release a schedule entry now: early, late, or again to carry a fixed file. | [Console](https://hertie-data-science-lab.github.io/dsl-teaching-toolkit/) | `python -m dsl_course release.entry --course-org hertie-nlp-e1282 --semester-org <semester-org> --arg entry=<entry>` |
| `release.adhoc` | Release a folder that is not in the schedule. | [Console](https://hertie-data-science-lab.github.io/dsl-teaching-toolkit/) | `python -m dsl_course release.adhoc --course-org hertie-nlp-e1282 --semester-org <semester-org> --arg course_source_repo=<course_source_repo> --arg course_source_path=<course_source_path>` |
| `release.propagate_back` | Keep this semester's edits for future terms: one pull request per source repo. | [Console](https://hertie-data-science-lab.github.io/dsl-teaching-toolkit/) | `python -m dsl_course release.propagate_back --course-org hertie-nlp-e1282 --semester-org <semester-org>` |
| `assignment.handout_now` | Hand out an assignment now. | [Console](https://hertie-data-science-lab.github.io/dsl-teaching-toolkit/) | `python -m dsl_course assignment.handout_now --course-org hertie-nlp-e1282 --semester-org <semester-org> --arg course_source_repo=<course_source_repo>` |
| `assignment.update_copies` | Update every copy of an assignment with a fixed file. | [Console](https://hertie-data-science-lab.github.io/dsl-teaching-toolkit/) | `python -m dsl_course assignment.update_copies --course-org hertie-nlp-e1282 --semester-org <semester-org> --arg course_source_repo=<course_source_repo> --arg path=<path>` |
| `assignment.collect_now` | Bring the marking sheet up to date with the latest submissions. | [Console](https://hertie-data-science-lab.github.io/dsl-teaching-toolkit/) | `python -m dsl_course assignment.collect_now --course-org hertie-nlp-e1282 --semester-org <semester-org> --arg course_source_repo=<course_source_repo>` |
| `grades.return` | Return marks and feedback to students. | [Console](https://hertie-data-science-lab.github.io/dsl-teaching-toolkit/) | `python -m dsl_course grades.return --course-org hertie-nlp-e1282 --semester-org <semester-org>` |
| `roster.send_codes` | Send new codes to every student who has not joined; old codes stop working. | [Console](https://hertie-data-science-lab.github.io/dsl-teaching-toolkit/) | `python -m dsl_course roster.send_codes --course-org hertie-nlp-e1282 --semester-org <semester-org>` |
| `site.update` | Update the semester site now. | [Console](https://hertie-data-science-lab.github.io/dsl-teaching-toolkit/) | `python -m dsl_course site.update --course-org hertie-nlp-e1282 --semester-org <semester-org>` |
| `teams.open_window` | Email every student still without a team for this assignment's open team-formation window. | [Console](https://hertie-data-science-lab.github.io/dsl-teaching-toolkit/) | `python -m dsl_course teams.open_window --course-org hertie-nlp-e1282 --semester-org <semester-org> --arg assignment=<assignment>` |
| `access.check` | Check instructor and student access against semester.yml, the roster and teams. | [Console](https://hertie-data-science-lab.github.io/dsl-teaching-toolkit/) | `python -m dsl_course access.check --course-org hertie-nlp-e1282 --semester-org <semester-org>` |
| `semester.archive` | Archive the semester: every repo read-only, nothing deleted. | [Console](https://hertie-data-science-lab.github.io/dsl-teaching-toolkit/) | `python -m dsl_course semester.archive --course-org hertie-nlp-e1282 --semester-org <semester-org>` |
| `course.publish_website` | Publish the public website as its settings (opencourse.yml) say. | [Console](https://hertie-data-science-lab.github.io/dsl-teaching-toolkit/) | `python -m dsl_course course.publish_website --course-org hertie-nlp-e1282` |
| `assignment.derive_starter` | Write the student starter onto main from the solution branch. | [Console](https://hertie-data-science-lab.github.io/dsl-teaching-toolkit/) | `python -m dsl_course assignment.derive_starter --course-org hertie-nlp-e1282 --arg course_source_repo=<course_source_repo>` |
| `assignment.generate_syllabus` | Write the weekly plan into the syllabus, from the semester's schedule. | [Console](https://hertie-data-science-lab.github.io/dsl-teaching-toolkit/) | `python -m dsl_course assignment.generate_syllabus --course-org hertie-nlp-e1282 --semester-org <semester-org> --arg course_source_repo=<course_source_repo>` |
| `materials.create` | Create a materials repo for a semester. | [Console](https://hertie-data-science-lab.github.io/dsl-teaching-toolkit/) | `python -m dsl_course materials.create --course-org hertie-nlp-e1282 --arg semester=<semester>` |
| `materials.confirm_withheld` | Confirm a materials repo's withheld patterns are reviewed, unchanged. | [Console](https://hertie-data-science-lab.github.io/dsl-teaching-toolkit/) | `python -m dsl_course materials.confirm_withheld --course-org hertie-nlp-e1282 --arg repo=<repo>` |
| `assignment.create` | Create an assignment template. | [Console](https://hertie-data-science-lab.github.io/dsl-teaching-toolkit/) | `python -m dsl_course assignment.create --course-org hertie-nlp-e1282 --arg name=<name>` |
| `semester.bootstrap` | Set up an empty semester org. | [Console](https://hertie-data-science-lab.github.io/dsl-teaching-toolkit/) | `python -m dsl_course semester.bootstrap --course-org hertie-nlp-e1282 --semester-org <semester-org>` |

## Workflows in this repo

The [`.github` Actions tab](https://github.com/hertie-nlp-e1282/.github/actions) runs these
_(automatically bootstrapped from the central
[dsl-teaching-toolkit repo](https://github.com/hertie-data-science-lab/dsl-teaching-toolkit))_:

| Workflow | What it does | Managed |
| --- | --- | --- |
| [**Collect submissions**](https://github.com/hertie-nlp-e1282/.github/actions/workflows/collect-submissions.yml) | Refresh an assignment's grading sheet now instead of waiting for the cron. The Console's *Collect now* runs it: grading runs student code in this workflow's own sandboxed job. | Console |
| [**Distribute grades**](https://github.com/hertie-nlp-e1282/.github/actions/workflows/distribute-grades.yml) | Send what the grading sheet holds: each student's private `grades-<handle>` repo, the semester grades file, and an email. The Console's *Return marks* and the scheduler both run it, in one queue. | Console |
| [**Send enrolment codes**](https://github.com/hertie-nlp-e1282/.github/actions/workflows/send-codes.yml) | Emails each student their enrolment code. There is no button: a push to a semester's `students.csv` fires it, and it sends for real. | Automatic |
| [**Sync membership**](https://github.com/hertie-nlp-e1282/.github/actions/workflows/sync-membership.yml) | Reconciles teams and access from `students.csv`, this org's `people:` block and each semester's `semester.yml`. Runs on a push to any of them and daily; a manual run walks every semester. | Auto-handled |
| [**Sync site**](https://github.com/hertie-nlp-e1282/.github/actions/workflows/sync-site.yml) | Regenerates every semester's website from the org structure. Releases and schedule pushes already do; a manual run walks every semester. | Auto-handled |
| [**Publish course website**](https://github.com/hertie-nlp-e1282/.github/actions/workflows/publish-site.yml) | **[OPTIONAL]** Builds the public open-courseware site `hertie-nlp-e1282.github.io` as `.github/course.yml` `open_course_site:` says (off by default); a daily cron re-syncs it once on. | Auto-handled |
| [**Refresh actions**](https://github.com/hertie-nlp-e1282/.github/actions/workflows/refresh-actions.yml) | Repopulates the dropdowns, re-equips content repos, and rebuilds this index. Runs itself nightly. | Auto-handled |
| [**Scheduled release**](https://github.com/hertie-nlp-e1282/.github/actions/workflows/scheduled-release.yml) | Auto-releases whatever each semester's `schedule.yml` says is now due, about every 15 minutes. Manual runs default to a preview. | Auto-handled |
| [**Console**](https://github.com/hertie-nlp-e1282/.github/actions/workflows/console.yml) | Runs what the Instructor Console asks for. Not for pressing by hand: the Console fills in the request and follows the run. | Auto-handled |

---


## Repository structure (required)

```
hertie-nlp-e1282/                            <- this COURSE org (persistent)
|-- .github/                      profile + faculty & instructor workflows (see Actions tab) + semester registry
|-- course-materials-<year>/      lectures/01_.../   readings/01_.../   (+ syllabus, README)
`-- assignment-<name>/            is_template repo (topic dsl-assignment):
                                    main      -> starter + autograder   (students get this)
                                    solution  -> solution/   (pushed to students on demand)

<Course>-f<year>/                 <- one SEMESTER org per year (New semester sets it up)
|-- join/                         Join issue -> onboard (enrol)
|-- semester-config/             students.csv  (private roster)
|-- materials/                    released lectures/readings  (students-team read)
|-- <org>.github.io/              auto-deployed website (synced from this structure)
`-- <assignment>-<handle>/        one private repo per student (default; see submit_via)
```

This whole structure is fully bootstrapped from the central [`dsl-teaching-toolkit`](https://github.com/hertie-data-science-lab/dsl-teaching-toolkit) repo (via its **Bootstrap Course Org** action), and the actions above run that same central code.

The course-level actions assume this layout - use **New course materials** / **New assignment** above to scaffold correctly. These scaffolds are designed to be generic & non-prescriptive, however if these formats to not suit your intended course delivery structure, please contact the DSL (`h.baker@hertie-school.org`).

### Materials repo

(`course-materials-<year>`) - the source a release copies from. Any path in it can be released. The convention below is what the downstream pipeline transformations expect: ordinal-prefixed (`01_`, `02_`, `03_`, ...) sub-directories, which is the only constraint. The following are seeded automatically, but edit them as you wish:
- `lectures/01_.../` - one folder per session's lecture files;
- `readings/01_.../` - one folder per session's readings;
- root files (`SYLLABUS.md`, `README.md`).

Add more sections freely (e.g. `labs/01_.../`, `datasets/01_.../`).

> Alternatively you could have `sessions/01_.../` with lectures & readings combined - or however you prefer to set it up. The only constraint is the ordinal-prefixed subdirectories.

### Assignment repo

`assignment-<name>` (an `is_template` repo) - the source a hand-out copies from, once a semester's schedule names it:
- **`main` branch** - the starter code only (no tests, no autograder). This is exactly what students receive (native template-generate copies `main` only).
- **`solution` branch** - the model solution (`solution/`), plus **`grading_config.yml`** and the **hidden tests** the autograder runs faculty-side at the cutoff. **All of this MUST live on this branch, never on `main`** - that is what guarantees it is never copied into student repos on generate. Only the `solution/` folder reaches students, and only when its `solution_datetime` passes, or you hand it out with **solution_datetime** `now` (a separate, later commit); the hidden tests and `grading_config.yml` never do.

## Further details on how the actions behave

**Releasing materials** (`release.entry` for a schedule entry, `release.adhoc` for anything
else) takes the same five fields as a `schedule.yml` `deploy:` entry: `semester_org`,
`course_source_repo`, `course_source_path`, `semester_dest_repo`, `semester_dest_path` - so
a release now and the scheduled release plan share one vocabulary. `course_source_path` is any folder or file (`lectures/03_regression`,
`mlpkg/simulation`, `SYLLABUS.md`); a folder is copied whole, **every file** in it.
`course_source_path` and `semester_dest_path` accept comma-separated lists paired in order, so
one release can carry several paths at once; a blank `semester_dest_path` mirrors each source
path. `semester_dest_repo` (default `materials`) is created on demand, private, with
`students` **and** `auditors` read. Copies are additive and idempotent: only what you have
released appears, and re-releasing changes nothing.

**Handing out an assignment** (`assignment.handout_now`) - two stages: (1) it freezes a semester-level template repo
`<assignment>` from your `assignment-*-<year>` template; (2) it generates one private
`<assignment>-<handle>` repo per onboarded student **from that semester template**, adding
each as collaborator. After the assignment deadline, hand it out again with **solution_datetime** `now` to push the
template's `solution` branch into every student repo. Solutions stay on the `solution`
branch so a normal release never leaks them. A template's `submit_via` can change stage
(2) instead: `external` creates no repo at all, and `shared_dropbox_repo` creates one
`<assignment>-submissions` drop box for the whole semester rather than one repo each.

**The semester website** - every semester has an auto-deployed site `<org>.github.io`. It is regenerated
on every release (and via **Sync site**). Its lecture links point at the semester's private repos, so
they only resolve for enrolled members (deliberate).

**The public course website** (optional) - `Publish course website` builds `hertie-nlp-e1282.github.io`, a public
open-courseware site for the course as a whole. Unlike the semester sites it **hosts** the shared lecture
files (the source repos are private, so links would 404); readings are published as a text-only reading
list unless the course lists them as files to publish. It is off by default and driven by `.github/course.yml` `open_course_site:` (the
console's Public website section) - releases and refresh never touch it - and once on, a daily cron
re-syncs it, so later materials edits reach it on their own.

---
Maintained by the [Hertie Data Science Lab](https://github.com/hertie-data-science-lab).
