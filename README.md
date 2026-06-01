# skin.myskin

A custom Kodi 21 Omega skin project inspired by the Netflix user interface, featuring a dark red and black theme with a redesigned home screen.

## Project Goal

Create a modern streaming-service-style Kodi skin with:

* Netflix-inspired layout
* Red and black color scheme
* Large featured content area
* Horizontal content rows
* Simplified navigation
* Custom home screen design

## Development Environment

* Kodi 21 Omega
* Visual Studio Code
* Git
* GitHub

## Changes Made

### 1. Created Custom Skin

A new skin was created under:

```text
Kodi/addons/skin.myskin
```

allowing experimentation without modifying existing installed skins.

### 2. Set Up Git Version Control

* Initialized a Git repository
* Created development branches
* Learned how to stage, commit, and push changes
* Configured Git remotes for GitHub integration

### 3. Modified Home.xml

The home screen layout was edited to:

* Add custom test controls
* Experiment with new UI elements
* Test Kodi XML rendering
* Verify that skin changes were loading correctly

Example test element added:

```xml
<control type="label">
    <label>HELLO KODI TEST</label>
</control>
```

### 4. Investigated Navigation Controls

Reviewed and analyzed:

* Control IDs
* Focus handling
* Navigation logic
* Widget interactions

Particular attention was given to:

```xml
id="9000"
```

which acts as a primary navigation control throughout the skin.

### 5. Explored Includes_Home.xml

Examined:

* Widget layouts
* Home screen categories
* Poster rows
* Focus animations
* Button controls
* Window(Home) references

### 6. Added Custom Background Testing

Tested custom imagery using:

```xml
<texture>media/home.jpg</texture>
```

and explored Kodi background layering behavior.

### 7. Learned Kodi Skin Structure

Studied relationships between:

* Home.xml
* Includes_Home.xml
* Includes.xml
* Media assets
* Control IDs
* Window properties

## Current Status

Working prototype with:

* Custom home screen edits
* Verified XML changes loading in Kodi
* Git repository configured
* Ready for Netflix-style UI redesign

## Future Plans

* Replace default menu with Netflix-style sidebar
* Add hero/banner content section
* Create horizontal content carousels
* Implement custom red/black theme
* Improve animations and transitions
* Add custom icons and branding
* Optimize widget performance

## Repository Workflow

Typical workflow:

```bash
git add .
git commit -m "Describe changes"
git push -u origin HEAD
```

## Notes

This project is intended as a learning exercise in:

* Kodi skin development
* XML UI design
* Git version control
* Open-source project management
* Frontend interface design
