# Python Packaging Council meeting notes (19 October 2026)

## Attendees

- Brett Cannon
- Deb Nicholson
- Henry Schreiner
- Pradyun Gedam
- Ralf Gommers

## Discussion Notes

- We talked about the Python core developer sprints and the topics we’d like to discuss there.
  - Improvements to the PEP process were a particular focus.
- We revisited how to [maintain the list of packaging PEP sponsors](https://github.com/python/packaging-council/issues/3).
  - We’d prefer guidelines that leave room for judgment, rather than making this too mechanical.
    - These should cover both granting and removing sponsorship privileges.
  - Brett will put together a PR.
- We discussed the boundary between packaging standards and PyPI policy.
  - Our focus is on index standards; PyPI policy belongs with the PSF, particularly where it involves legal responsibilities.
  - We’re available for consultation, without taking on the operation of Warehouse or individual packaging tools.
  - We also want to avoid surprising the community with new rules.
- We started reviewing the [outstanding packaging PEPs](https://peps.python.org/topic/packaging/).
  - We’ll follow up in small batches rather than poke everyone at once.
  - Some proposals need a conversation with their authors or delegates:
    - **PEP 694 (Upload 2.0):** We’ll talk to the authors.
    - **PEP 711 (PyBI):** We think this may be inactive; Pradyun will follow up on its status.
    - **PEP 847 (Problem Details for the Simple Repository API):** This is awaiting a pronouncement. We’ll check with Donald that the decision should come to the PPC.
    - We also want to talk with Paul Moore about his views on the outstanding PEPs.
  - Several proposals have more work or discussion coming:
    - **PEPs 725 and 804 (external dependencies):** Ralf, wearing his author hat, plans to write a short overview to get PPC feedback.
    - **PEP 780 (ABI features as environment markers):** More is expected soon.
    - **PEPs 817 and 850 (wheel variants):** Further work is expected, though the timing is less clear.
    - **PEP 819 (JSON package metadata):** We expect this may need us to encourage movement across the ecosystem.
  - Others can wait for now:
    - **PEP 480:** No action from us at this point.
    - **PEP 710 (installed-package provenance):** We questioned whether this still needs to proceed, given the likely overlap with SBOMs.
    - **PEP 766 (multiple-index priority):** Parked for now; its author isn’t currently working on it.
    - **PEP 771 (default extras):** Already under active discussion.
    - **PEP 777 (wheel format):** We’ll wait for the authors to move it forward.
    - **PEP 807 (Trusted Publishing):** We’ll wait for input from the people involved.
- We followed up on public office hours.
  - We still need to announce them!
  - The plan from last week is to try 30-minute video calls every two weeks using the Google Meet link.
