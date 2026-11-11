# Change log

## Fork (BrikHMP18/ocbench)
- BlockEnv: optional `object_size=(lx, ly, lz)` for non-cube blocks; the scripted expert then always grasps across `ly`, or across `lx` with a 90-degree turn when `ly` does not fit the 8.5 cm gripper.
- BlockController: optional `grasp_turns=False` stops the expert from turning cube grasps by 90 degrees.

## ocbench 1.0.2 (2026-10-13)
- Fix Switch collision-buffer overflow with MuJoCo 3.12+.

## ocbench 1.0.1 (2026-10-04)
- Update the package description.

## ocbench 1.0.0 (2026-10-04)
- Initial release.
