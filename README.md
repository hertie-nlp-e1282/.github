<!-- SYSTEM-OWNED - do not edit, edits here are overwritten on the next refresh. -->

# Natural Language Processing - course control panel

This is the **`.github` repo** for the `hertie-nlp-e1282` course org - the primary control panel faculty & instructors use
to run and configure the course.

## Run an operation

Every operation is a button in the **Instructor Console** and a command, `python -m dsl_course <op>`, from a laptop. Either needs you to be (1) in this org's `course-admin` team (declared here, course-wide), or (2) in a semester's `instructors` team (declared in that semester's own `semester-config/semester.yml`). The full list, with each command, is on the **[org home page](https://github.com/hertie-nlp-e1282)**. The [Actions tab](https://github.com/hertie-nlp-e1282/.github/actions) holds the automatic workflows those operations and the schedule run.

## Typical flow

1. **New course materials** / **New assignment** - scaffold your content repos, then fill them in.
   Write the answer once on the `solution` branch and let **Derive student version** write `main`'s starter from it.
2. Create an empty **semester org** for the year, add the bot as an Owner, then **New semester** sets it up.
3. Each session: pre-schedule releases and hand-outs in `schedule.yml` (recommended), or **Release** / **Hand out** now.
4. Grading: the sheet appears at handout -> **Collect submissions** (or wait for the cron) -> type the marks -> **Return marks** (preview first).
5. End of term: **Archive** - freezes the year's student repos and seals the semester's private record. Nothing is deleted.

## What's in here

- `.github/workflows/` - the workflows. SYSTEM-OWNED: do not edit or delete them.
- `course.yml` - this course's identity (name/code) and the registry of `course_admins`, who persist across years. INSTRUCTOR-OWNED. (Per-semester instructors/TAs and the schedule are declared in the semester org - not here).
- `profile/README.md` - the public org landing page (an auto-generated repo index). SYSTEM-OWNED: do not edit it.

Built and kept in sync by the [DSL teaching toolkit](https://github.com/hertie-data-science-lab/dsl-teaching-toolkit).
