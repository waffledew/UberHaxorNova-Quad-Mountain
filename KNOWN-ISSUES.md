# Known issues

- The Bat mod from the original series has not been identified. AtomicStryker's Pet Bats is from a later Minecraft generation and is not compatible.
- This is a large legacy ModLoader/Forge stack. Adding another jar mod can silently replace a patched Minecraft class and break an unrelated feature.
- Not Enough Items must remain in the jar-mod list. Putting NEI 1.1.2 in `.minecraft/mods` makes it appear loaded without attaching its inventory interface.
- Inventory Tweaks originally shared NEI's `R` key. The clean instance maps Inventory Tweaks sorting to `K`.
- Some legacy sounds depend on the included `.minecraft/resources/mod` directory and the repaired AudioMod path.
- Modern Java releases may crash or render incorrectly. Java 8 is recommended.
