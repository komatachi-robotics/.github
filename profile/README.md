<h1 align="center">駒たち &nbsp;Komatachi</h1>
<p align="center"><em>koma</em> — a piece on a board. <em>-tachi</em> — the plural for living things.<br>
<strong>The pieces. Never one of them.</strong></p>

<p align="center">
  <a href="https://komatachi.com"><img src="https://img.shields.io/badge/komatachi.com-2a4d8f?style=flat&logoColor=white" alt="website"></a>
  <img src="https://img.shields.io/badge/status-pre--prototype-9a6400?style=flat" alt="status">
  <img src="https://img.shields.io/badge/built%20in-Europe-0f7a3d?style=flat" alt="Europe">
  <img src="https://img.shields.io/badge/LeRobot-compatible-2a4d8f?style=flat" alt="LeRobot">
</p>

---

A single robot in a room is a demonstration. Robots that hand things to each
other, take over a task mid-way, and cover for the one that is charging are
infrastructure. We are building for the second case, and named the company
after it.

That belief starts inside the machine. Most robots at this price hang both arms
off one mast, so the arms always share a height and can only ever do one thing
at a time. **Ours gives each arm its own metre of vertical travel**, so one can
hold at counter height while the other reaches the floor — two limbs
cooperating before two robots ever do.

Moving the lift out of the centre also leaves the middle of the robot empty.
That space is a **cargo bay**. A manipulator picks things up; a manipulator with
a bay carries them.

## K0

| | |
|---|---|
| Arms | 2 × 6-DoF, SO-101 compatible |
| Lift | 2 × 1000 mm, independent, self-locking — holds position with the power off |
| Body | open-front cargo bay |
| Compute | Raspberry Pi 5 — inference runs off-board, which is why it stays cheap |
| Software | LeRobot datasets, ROS 2 bridge, browser teleoperation |
| Target price | €2,490 ex-VAT |

Teleoperated on day one. Every session records as a LeRobot dataset, so the
robots you own are also the fleet that produces the training data.

## Where we are

**No prototype exists yet.** The design is frozen, the bill of materials is
costed against real EU suppliers, and reservations are open. Specifications are
published as either *Confirmed* — design frozen, parts specified — or *Target* —
design intent, not yet measured on hardware. We label them because the
alternative is lying to you.

## Built on open work

Standing on [SO-ARM100/101](https://github.com/TheRobotStudio/SO-ARM100) by The
Robot Studio, [XLeRobot](https://github.com/Vector-Wangel/XLeRobot), and
[LeRobot](https://github.com/huggingface/lerobot). Open hardware got the cost of
a capable arm down to the point where this is possible at all.

<p align="center"><sub><a href="https://komatachi.com">komatachi.com</a> · <a href="mailto:hello@komatachi.com">hello@komatachi.com</a> · Budapest</sub></p>
