# El Gayar — Short Film | Blender Project

A chaotic short film where a random Egyptian guy opens a portal and ends up teaming with iconic characters to fight a wizard.

---

## Story Summary

**Scene 1:** El Gayar is in his kitchen doing his thing. A portal opens behind him.

**Scene 2:** He steps through. Sonic and Spiderman are arguing, Lara is fixing her hair, Master Chief is pacing. Spiderman notices El Gayar.

**Scene 3:** Master Chief leads the group through a forest. Spiderman swings overhead.

**Scene 4:** Group traversal continues. Small character interactions.

**Scene 5:** They enter a castle. Door slams shut. Wizard appears with snakes.

**Scene 6:** Fight scene. Everyone struggles.
El Gayar activates **Domain Expansion: Borgar bel Btengan**.
Everything goes black. Wizard pulls a Glock. A giant burger kills him.
Portal opens. El Gayar leaves. **End.**

---

## Characters

| Character             | Owner       | File                                                     |
| --------------------- | ----------- | -------------------------------------------------------- |
| El Gayar              | Mostafa Eid | characters/tamer el gayar/gayar.blend                    |
| Spiderman             | Mostafa Eid | characters/spider man/spiderman.blend                    |
| Lara Croft            | Mostafa Eid | characters/lara croft/lara croft.blend                   |
| Sonic                 | Mostafa Eid | characters/sonic/sonic.blend                             |
| Master Chief          | Mostafa Eid | characters/master cheif/mastercheif.blend                |
| Master Chief (Rigged) | Mostafa Eid | characters/master cheif already rigged/mastercheif.blend |
| Villain (Wizard)      | TBD         | characters/evil wizard ( to be named)/                   |
| Snake                 | TBD         | characters/snake (hand made)/                            |

---

## Scenes

| Scene    | Description                  | Owner | Folder                                     |
| -------- | ---------------------------- | ----- | ------------------------------------------ |
| Scene 01 | El Gayar room (portal opens) | TBD   | scenes/gayar's room/                       |
| Scene 02 | Meeting room with characters | TBD   | scenes/he room where they meet in scene 2/ |
| Scene 03 | Forest traversal             | TBD   | (not created yet)                          |
| Scene 04 | Group walking                | TBD   | scenes/scene04/                            |
| Scene 05 | Castle entrance              | TBD   | scenes/scene05/                            |
| Scene 06 | Fight + ending               | TBD   | scenes/scene06/                            |

---

## Folder Structure

```
/el-gayar
  /characters
    /tamer el gayar
    /spider man
    /lara croft
    /sonic
    /master cheif
    /master cheif already rigged
    /evil wizard ( to be named)
    /snake (hand made)

  /scenes
    /gayar's room
    /he room where they meet in scene 2
    /scene04
    /scene05
    /scene06
    /the front of the castle

  /shared
    /textures
    /hdri
    /props
      /enviroment
      /weapons

  /renders
    /frames   (ignored)
    /preview
    /final
```

---

## Rules (IMPORTANT)

### File Ownership

* One person owns one .blend file
* Do NOT edit someone else's file without asking
* Never work on the same file simultaneously

---

### Linking (CRITICAL)

* Use File → Link, NOT Append
* Scenes should reference characters, not duplicate them
* Updates to characters = auto update in scenes

---

### Textures

* Keep textures inside each character’s /textures
* Shared textures go in /shared/textures
* DO NOT rename or move folders (breaks paths)
* Enable relative paths:

  Edit → Preferences → zFile Paths → Relative Paths

---

### Git Workflow

* Always pull before starting work:

  git pull

* Commit often:

  "sonic: added textures"
  "scene04: blocking environment"

* Before leaving:

  git push

---

### DO NOT COMMIT

* .blend1, .blend2
* /renders/frames/

---

## Git LFS (REQUIRED)

Run once after cloning:

```
git lfs install
```

Without this, .blend and textures won’t load correctly.

---

## Notes / Fixes Needed

* Naming issues:

  * he room where they meet in scene 2 → rename later

* Duplicate Master Chief folder → choose one

---

## Final Edit

Final video will be assembled in:

```
/renders/final/
```

(or later /edit/final_edit.blend)

---

## Goal

* Finish all scenes
* Keep files linked (NOT duplicated)
* Export final cinematic render
