# fortnite-offsets

Gworld = 0xED56188 // Uworld and Gworld are the same thing.
FName = 0xED7C140
GameInstance = 0x1B8
LocalPlayerArray = 0x38
CurrentWeapon = 0x8D8
PlayerState = 0x2A8
Mesh = 0x310
ItemDefinition = 0x18
Tier = 0x73
DisplayName = 0x90
PlayerController = 0x30
AcknowledgedPawn = 0x330
RootComponent = 0x190
RelativeLocation = 0x128
TeamIndex = 0x1100
bonearray = read<uintptr_t>(mesh + 0x5d0);
    if (!bonearray) bonearray = read<uintptr_t>(mesh + 0x5d0 + 0x10);
