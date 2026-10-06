# Lab 4: Donkey Kong VibeCoding

| Student | Details |
| --- | --- |
| Name | Shriya Vasundhara Singh |
| SRN | PES1UG24AM269 |
| GitHub | [vasun26shriya](https://github.com/vasun26shriya) |
| Assigned project | [SETAPESU26/30_donkeykong](https://github.com/SETAPESU26/30_donkeykong) |

## Project overview

This Lab 4 submission fixes and extends a Donkey Kong-style game written in Python with Pygame. The completed source code and its original Git history are included in the project ZIP.

## Deliverables

- [Before video](Lab-4/videos/before_fix.mp4) - approximately 10 seconds of gameplay before the changes.
- [After video](Lab-4/videos/after_fix.mp4) - approximately 10 seconds of gameplay after the changes.
- [Chat-history PDF](Lab-4/chat_history/Lab4_Chat_History.pdf) - the supplied record of the AI-assisted development session.
- [Complete project ZIP](Lab-4/30_donkeykong_Lab4_submission.zip) - updated code, documentation, recording tool, deliverables, and the original Git history with separate task commits.

## Completed tasks

1. **Ladder-descent fix:** changed the barrel ladder probability from 70% to approximately 30%.
2. **Score-based theme:** the background warms from navy to ember red as the score increases.
3. **Jump effect:** floating, fading labels show the points awarded when a barrel is cleared.
4. **Score multiplier:** barrel-jump bonuses double once the score reaches 300 points; labels display the actual bonus.

## Run the game

Download and extract the project ZIP. Open a terminal in the extracted `30_donkeykong/Lab-4` folder, then run:

```bash
python -m pip install pygame
python game.py
```

Requires Python 3.10 or newer.

**Controls:** Left/Right to move, Space to jump, Up/Down to climb ladders, and R to reset.

## Recording and commit history

The videos were produced from the real game loop using the included headless recording tool with scripted input, as documented in the chat-history PDF and submission notes.

The ZIP contains the original repository's `.git` folder, including a separate commit for each of the four implementation tasks. Those implementation commits are preserved inside the ZIP; this repository's visible commit history records the submission uploads and organization.

No pull request was opened to SETAPESU26.

