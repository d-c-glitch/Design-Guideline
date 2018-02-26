## Attach Design file(s) / asset(s) on JIRA story:

- Check to ensure design templates (e.g. Adobe Photoshop, Sketch) or InVision link (which come with inspect tools) are supplied so that engineer(s) can access the templates / references.
- All required assets (e.g. images, svg icons) have been optimized for web.

## Design Implementation Instructions / Guide:

#### Interactions:
- Help BA / PO understand how the user journey is panning out. Help engineers plan / design / approach code.

#### States:
- Ensure all interactive elements are included in the design (Example - hover, focus, active, default...etc) and are detailed clearly.
- Design for dynamic content. E.g. Is there state not included in the story? isn't any content to display (Example - search result), was there any design (with message) for that?
- Has the design clearly communicate the changes / differences of each different state? (Example - Collapsible with 'Expand' and 'Collapse' state).

## Design with consideration of Locomote supported platform and devices:
- Does the design meet locomote current supported viewport's requirements (Example - if iPhone5 is our smallest supported mobile device, does the design supplied caterred for it?)
- Is a mobile and desktop design necessary? and is it ready?

## Copy (content):
- Is the copy gramatically correct?
- Ensure the sample data content used within design shows the correct format to avoid confusion.

> Example:
>
> `SW7F9Q` - PNR will be always be the combination of 6 characters in alphabetic and numeric only. Never use  false / misleading example information such as LM-1337

## Styling Consistency:

#### Font:
Ensure the font weight (e.g. `bold`, `semi-bold`) used in design is the same weight as the web font's output

> Example:
>
> Complaints regarding engineers not using the correct font-weight from the design. Supplied design was showing in `bold`; so engineers apply `bold`. Unfortunately some expect it to be consistent and show `semi-bold`.

#### Color:
Ensure that color used in the design is consistent with the styleguide.

> Example:
>
> If there is any color that looks similar to #008cd2 (locomote blue / brand color) was it done intentionally? or was it intended to be the same as locomote blue?

## Confusions:
Ensure no contradicting designes exist attached to story.

> Example:
>
> Supplied design mockup image's `checked` radio button has a **grey** border color. But supplied `checked` radio button svg's border color is **blue**.

Ensure states are labeled correctly.

> Example:
>
> When supplied `hover` state is in design but no `focus` state exists. If the intention was to have the `hover` state to be same as the `focus` state please make sure it's detailed in the story.

#### Scope of changes:
Ensure all supplied design mockups / templates do not contain any unnecessary work outside the scope of the story.

## Development Ready:
Ensure all supplied design files and assets have been signed off or approved prior to commencing the card. Do not update design files / assets on JIRA without communicating with the team.
