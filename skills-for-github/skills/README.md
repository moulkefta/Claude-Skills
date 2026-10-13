# Pulzzer Claude Code skills

31 frontend / design / research skills, used by Claude Code when working on
Pulzzer Scout.

## Use in a cloud Claude Code session

From the root of the repo you are working in:

    git clone --depth 1 https://github.com/moulkefta/pulzzer-skills .claude/skills-src
    mkdir -p .claude/skills
    cp -r .claude/skills-src/* .claude/skills/
    rm -rf .claude/skills-src

Claude Code picks up every folder under `.claude/skills/` automatically.

## Contents

Each folder has a SKILL.md. Nine also carry a supporting file.

Manual-only (they never fire on their own, you have to name them):
pick-ui-library, prototype, review-animations.
