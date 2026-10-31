# Publication and review notes

This package is a public portfolio selection from the CampusSignal RAD-v1 materials. It preserves the distinction between the team's course deliverables, a revised reference diagram and the publication preparation.

## Sources reviewed

The 52-page Group1_RAD_v1 PDF and its final Word counterpart, the earlier Word draft, the Figma work guide, the supplied PlantUML reference, the pasted Figma inventory and the 46 image files in the OOAD folder were inspected. The task-allocation document, project proposal and course specification were also used to establish scope and attribution.

The public report is based on Group1_RAD_v1.pdf. The final Word file agrees on the main RAD-v1 scope and the documented prototype limitations. The older Word copy contains review comments and earlier screen specifications and is not used as a parallel final deliverable.

## Public report preparation

- Removed the six student numbers from the cover and work-distribution appendix; retained all six team names and their documented responsibilities.
- Omitted original PDF pages 43 to 46, covering unconfirmed retrospective meeting minutes and follow-up actions. The source itself labels these records as drafts awaiting team confirmation.
- Removed an obsolete review-context sentence saying that the approved proposal was unavailable to the reviewer. The proposal was available during this packaging review.
- Kept the original printed page labels, requirements, scenarios, use-case flows, traceability, glossary, submitted diagram and prototype-verification limitations. The resulting public copy has 48 physical pages.
- Preserved the design/prototype link targets while removing the transient `t` query parameter from the design link.
- Replaced PDF document metadata with a project-level title and author label. The original Word and PDF files were not overwritten.

## Diagram review

The submitted Figure 1 has telemetry `include` arrowheads directed toward UC-02 and UC-05, while the report text describes those use cases as including the telemetry retrieval attempt. It also contains an unconnected Create / Update Candidate Issue use case.

The `critical-use-cases-reference` files are a separate focused portfolio revision. They direct UC-02 and UC-05 to the included telemetry retrieval behavior and connect the candidate-issue behavior as a conditional extension of UC-01, following the supplied reference and textual flows. Common utility use cases are omitted for readability.

The report's original Figure 1 is retained as an archival artifact. The supplied standalone PlantUML file was identified in the report as a reconstruction rather than the recovered original source, so it is not labelled as Efe's original editable diagram. The new reference PlantUML is explicitly marked as a portfolio revision; its automatic layout may differ from the fixed SVG rendering.

## Prototype review

The report records incomplete UC-04 click reactions for UI-30 Start verification test, UI-32 Back, UI-33 Reopen and UI-34 Return. It also does not separately verify a dedicated Reopened-to-In-Progress resume snapshot. These are documented limitations of the 25 October snapshot, not a live inspection of the current Figma file.

The original pasted text is a Caner/UC-05 Figma inventory with seven screen records. It is design metadata, not application source code. It is not included as an implemented software component.

## Files omitted from the public selection

Private group messages, Teams feedback screenshots, Figma editor/browser screenshots, duplicate images, the internal Figma work guide, raw inventory text, course handouts/templates, the commented older Word draft and unredacted Word/PDF originals are not included. Clean screen exports and the report's figures are used instead.

## Attribution and assistance

Project ownership remains with the six-person team. The responsibilities in README follow the supplied RAD-v1 Annex I and task-allocation materials. Publication cleanup, the English repository presentation and the separate reference-diagram revision were prepared with ChatGPT assistance. They are not claimed as additional original application implementation by a team member.
