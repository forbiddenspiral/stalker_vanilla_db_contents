# Table of contents

## levels

- [levels.db0](#lv0)
- [levels.db1](#lv1)

## localization

- [base_sounds.db](#bs)
- [xefis_movies.db](#xm)
- [xenglish.db](#xe)

## patches

- [xpatch_02.db](#xp02)

## resources

- [configs.db](#cf)
- [resources.db0](#rs0)
- [resources.db1](#rs1)
- [resources.db2](#rs2)
- [resources.db3](#rs3)
- [resources.db4](#rs4)

## levels - directory

<a id="lv0"></a>

### levels.db0

```console
└── levels
    ├── jupiter
    │   ├── meshes
    │   └── terrain
    ├── jupiter_underground
    │   └── meshes
    ├── labx8
    ├── pripyat
    │   ├── meshes
    │   └── terrain
    └── zaton
        ├── meshes
        └── terrain
```

<a id="lv1"></a>

### levels.db1

```console
└── levels
    └── zaton
        ├── meshes
        └── terrain
```

## localization - directory

<a id="bs"></a>

### base_sounds.db

```console
└── sounds
    └── characters_voice
        ├── dialogs
        ├── human_01
        │   ├── bandit
        │   │   ├── alife
        │   │   │   ├── attack
        │   │   │   ├── counter_attack
        │   │   │   ├── defence
        │   │   │   └── patrol
        │   │   ├── fight
        │   │   │   ├── attack
        │   │   │   ├── backup
        │   │   │   ├── cover_fire
        │   │   │   ├── death
        │   │   │   ├── detour
        │   │   │   ├── enemy
        │   │   │   ├── friend_hitted
        │   │   │   ├── friendly_fire
        │   │   │   ├── friendly_grenade
        │   │   │   ├── grenade
        │   │   │   ├── hit
        │   │   │   ├── post_combat_wait
        │   │   │   ├── searching_enemy
        │   │   │   └── tolls
        │   │   ├── hail
        │   │   ├── help
        │   │   │   ├── not_wounded
        │   │   │   ├── wounded
        │   │   │   ├── wounded_heavy
        │   │   │   ├── wounded_not_see_helper
        │   │   │   ├── wounded_psy
        │   │   │   ├── wounded_see_helper
        │   │   │   └── wounded_thanx
        │   │   ├── music
        │   │   ├── reactions
        │   │   │   ├── joke
        │   │   │   ├── music
        │   │   │   └── story
        │   │   ├── states
        │   │   │   ├── breath
        │   │   │   ├── idle
        │   │   │   ├── loot
        │   │   │   ├── meet
        │   │   │   ├── panic_human
        │   │   │   ├── panic_monster
        │   │   │   └── sleep
        │   │   ├── talk
        │   │   │   ├── intros
        │   │   │   ├── jokes
        │   │   │   └── use
        │   │   └── threat
        │   │       ├── back_off
        │   │       └── drop_weapon
        │   ├── dolg
        │   │   ├── alife
        │   │   │   ├── attack
        │   │   │   ├── counter_attack
        │   │   │   ├── defence
        │   │   │   └── patrol
        │   │   ├── fight
        │   │   │   ├── attack
        │   │   │   ├── backup
        │   │   │   ├── cover_fire
        │   │   │   ├── death
        │   │   │   ├── detour
        │   │   │   ├── enemy
        │   │   │   ├── enemy_down
        │   │   │   ├── enemy_hit
        │   │   │   ├── fire
        │   │   │   ├── friend_hitted
        │   │   │   ├── friendly_fire
        │   │   │   ├── friendly_grenade
        │   │   │   ├── grenade
        │   │   │   ├── hit
        │   │   │   ├── post_combat_wait
        │   │   │   ├── searching_enemy
        │   │   │   ├── threat
        │   │   │   └── tolls
        │   │   ├── hail
        │   │   ├── help
        │   │   │   ├── combat
        │   │   │   ├── not_wounded
        │   │   │   ├── wounded
        │   │   │   ├── wounded_heavy
        │   │   │   ├── wounded_not_see_helper
        │   │   │   ├── wounded_psy
        │   │   │   ├── wounded_see_helper
        │   │   │   └── wounded_thanx
        │   │   ├── music
        │   │   ├── reactions
        │   │   │   ├── box
        │   │   │   ├── joke
        │   │   │   ├── music
        │   │   │   └── story
        │   │   ├── states
        │   │   │   ├── breath
        │   │   │   ├── idle
        │   │   │   ├── loot
        │   │   │   ├── meet
        │   │   │   ├── panic_human
        │   │   │   ├── panic_monster
        │   │   │   ├── sleep
        │   │   │   └── trade
        │   │   ├── talk
        │   │   │   ├── intros
        │   │   │   ├── jokes
        │   │   │   └── use
        │   │   └── threat
        │   │       ├── back_off
        │   │       └── drop_weapon
        │   ├── freedom
        │   │   ├── alife
        │   │   │   ├── attack
        │   │   │   ├── counter_attack
        │   │   │   ├── defence
        │   │   │   └── patrol
        │   │   ├── fight
        │   │   │   ├── attack
        │   │   │   ├── backup
        │   │   │   ├── cover_fire
        │   │   │   ├── death
        │   │   │   ├── detour
        │   │   │   ├── enemy
        │   │   │   ├── enemy_down
        │   │   │   ├── enemy_hit
        │   │   │   ├── fire
        │   │   │   ├── friend_hitted
        │   │   │   ├── friendly_fire
        │   │   │   ├── friendly_grenade
        │   │   │   ├── grenade
        │   │   │   ├── hit
        │   │   │   ├── post_combat_wait
        │   │   │   ├── searching_enemy
        │   │   │   ├── threat
        │   │   │   └── tolls
        │   │   ├── hail
        │   │   ├── help
        │   │   │   ├── combat
        │   │   │   ├── not_wounded
        │   │   │   ├── wounded
        │   │   │   ├── wounded_heavy
        │   │   │   ├── wounded_not_see_helper
        │   │   │   ├── wounded_psy
        │   │   │   ├── wounded_see_helper
        │   │   │   └── wounded_thanx
        │   │   ├── music
        │   │   ├── reactions
        │   │   │   ├── box
        │   │   │   ├── joke
        │   │   │   ├── music
        │   │   │   └── story
        │   │   ├── states
        │   │   │   ├── breath
        │   │   │   ├── idle
        │   │   │   ├── loot
        │   │   │   ├── meet
        │   │   │   ├── panic_human
        │   │   │   ├── panic_monster
        │   │   │   ├── sleep
        │   │   │   └── trade
        │   │   ├── talk
        │   │   │   ├── intros
        │   │   │   ├── jokes
        │   │   │   └── use
        │   │   └── threat
        │   │       ├── back_off
        │   │       └── drop_weapon
        │   ├── killer
        │   │   ├── fight
        │   │   │   ├── attack
        │   │   │   ├── backup
        │   │   │   ├── cover_fire
        │   │   │   ├── death
        │   │   │   ├── detour
        │   │   │   ├── enemy
        │   │   │   ├── friend_hitted
        │   │   │   ├── friendly_fire
        │   │   │   ├── friendly_grenade
        │   │   │   ├── grenade
        │   │   │   ├── hit
        │   │   │   ├── searching_enemy
        │   │   │   └── tolls
        │   │   ├── hail
        │   │   ├── help
        │   │   │   ├── not_wounded
        │   │   │   ├── wounded
        │   │   │   ├── wounded_heavy
        │   │   │   │   └── aptechku
        │   │   │   ├── wounded_not_see_helper
        │   │   │   ├── wounded_psy
        │   │   │   ├── wounded_see_helper
        │   │   │   └── wounded_thanx
        │   │   ├── reactions
        │   │   │   ├── joke
        │   │   │   ├── music
        │   │   │   └── story
        │   │   ├── states
        │   │   │   ├── breath
        │   │   │   ├── idle
        │   │   │   ├── loot
        │   │   │   ├── panic_human
        │   │   │   ├── panic_monster
        │   │   │   └── sleep
        │   │   ├── talk
        │   │   │   ├── intros
        │   │   │   ├── jokes
        │   │   │   └── use
        │   │   └── threat
        │   │       ├── back_off
        │   │       └── drop_weapon
        │   ├── military
        │   │   ├── alife
        │   │   │   ├── attack
        │   │   │   ├── counter_attack
        │   │   │   └── patrol
        │   │   ├── fight
        │   │   │   ├── attack
        │   │   │   ├── backup
        │   │   │   ├── cover_fire
        │   │   │   ├── death
        │   │   │   ├── detour
        │   │   │   ├── enemy
        │   │   │   ├── enemy_down
        │   │   │   ├── enemy_hit
        │   │   │   ├── fire
        │   │   │   ├── friend_hitted
        │   │   │   ├── friendly_fire
        │   │   │   ├── grenade
        │   │   │   ├── hit
        │   │   │   ├── post_combat_wait
        │   │   │   ├── searching_enemy
        │   │   │   ├── threat
        │   │   │   └── tolls
        │   │   ├── hail
        │   │   ├── help
        │   │   │   ├── not_wounded
        │   │   │   ├── wounded
        │   │   │   ├── wounded_heavy
        │   │   │   ├── wounded_not_see_helper
        │   │   │   ├── wounded_psy
        │   │   │   ├── wounded_see_helper
        │   │   │   └── wounded_thanx
        │   │   ├── music
        │   │   ├── reactions
        │   │   │   ├── joke
        │   │   │   ├── music
        │   │   │   └── story
        │   │   ├── states
        │   │   │   ├── breath
        │   │   │   ├── idle
        │   │   │   ├── loot
        │   │   │   ├── meet
        │   │   │   ├── panic_human
        │   │   │   ├── panic_monster
        │   │   │   └── sleep
        │   │   ├── talk
        │   │   │   ├── intros
        │   │   │   ├── jokes
        │   │   │   └── use
        │   │   └── threat
        │   │       ├── back_off
        │   │       └── drop_weapon
        │   ├── monolith
        │   │   ├── fight
        │   │   │   ├── attack
        │   │   │   ├── backup
        │   │   │   ├── cover_fire
        │   │   │   ├── death
        │   │   │   ├── detour
        │   │   │   ├── enemy
        │   │   │   ├── enemy_down
        │   │   │   ├── enemy_hit
        │   │   │   ├── fire
        │   │   │   ├── friend_hitted
        │   │   │   ├── friendly_fire
        │   │   │   ├── grenade
        │   │   │   ├── hit
        │   │   │   ├── searching_enemy
        │   │   │   ├── threat
        │   │   │   └── tolls
        │   │   ├── help
        │   │   │   ├── wounded
        │   │   │   ├── wounded_heavy
        │   │   │   └── wounded_thanx
        │   │   ├── music
        │   │   ├── reactions
        │   │   │   ├── joke
        │   │   │   ├── music
        │   │   │   └── story
        │   │   ├── states
        │   │   │   ├── breath
        │   │   │   ├── idle
        │   │   │   ├── loot
        │   │   │   ├── panic_human
        │   │   │   ├── panic_monster
        │   │   │   └── sleep
        │   │   ├── talk
        │   │   │   ├── intros
        │   │   │   ├── jokes
        │   │   │   └── use
        │   │   └── threat
        │   │       ├── back_off
        │   │       └── drop_weapon
        │   ├── stalker
        │   │   ├── alife
        │   │   │   ├── attack
        │   │   │   ├── counter_attack
        │   │   │   ├── defence
        │   │   │   ├── patrol
        │   │   │   └── sos
        │   │   ├── fight
        │   │   │   ├── attack
        │   │   │   ├── backup
        │   │   │   ├── cover_fire
        │   │   │   ├── death
        │   │   │   ├── detour
        │   │   │   ├── enemy
        │   │   │   ├── enemy_down
        │   │   │   ├── enemy_hit
        │   │   │   ├── fire
        │   │   │   ├── friend_hitted
        │   │   │   ├── friendly_fire
        │   │   │   ├── friendly_grenade
        │   │   │   ├── grenade
        │   │   │   ├── hit
        │   │   │   ├── post_combat_wait
        │   │   │   ├── searching_enemy
        │   │   │   ├── threat
        │   │   │   └── tolls
        │   │   ├── help
        │   │   │   ├── combat
        │   │   │   ├── wounded
        │   │   │   ├── wounded_heavy
        │   │   │   └── wounded_thanx
        │   │   ├── music
        │   │   ├── reactions
        │   │   │   ├── box
        │   │   │   ├── joke
        │   │   │   ├── music
        │   │   │   └── story
        │   │   ├── states
        │   │   │   ├── breath
        │   │   │   ├── idle
        │   │   │   ├── loot
        │   │   │   ├── meet
        │   │   │   ├── panic_human
        │   │   │   ├── panic_monster
        │   │   │   ├── sleep
        │   │   │   └── trade
        │   │   ├── talk
        │   │   │   ├── intros
        │   │   │   ├── jokes
        │   │   │   └── use
        │   │   └── threat
        │   │       ├── back_off
        │   │       └── drop_weapon
        │   └── zombied
        │       ├── fight
        │       │   ├── attack
        │       │   ├── death
        │       │   ├── enemy
        │       │   └── hit
        │       └── states
        │           ├── idle
        │           └── rising
        ├── human_02
        │   ├── bandit
        │   │   ├── alife
        │   │   │   ├── attack
        │   │   │   ├── counter_attack
        │   │   │   ├── defence
        │   │   │   └── patrol
        │   │   ├── fight
        │   │   │   ├── attack
        │   │   │   ├── backup
        │   │   │   ├── cover_fire
        │   │   │   ├── danger_sound
        │   │   │   ├── death
        │   │   │   ├── detour
        │   │   │   ├── enemy
        │   │   │   ├── friend_hitted
        │   │   │   ├── friendly_fire
        │   │   │   ├── friendly_grenade
        │   │   │   ├── grenade
        │   │   │   ├── hit
        │   │   │   ├── post_combat_wait
        │   │   │   ├── searching_enemy
        │   │   │   └── tolls
        │   │   ├── hail
        │   │   ├── help
        │   │   │   ├── not_wounded
        │   │   │   ├── wounded
        │   │   │   ├── wounded_heavy
        │   │   │   ├── wounded_not_see_helper
        │   │   │   ├── wounded_psy
        │   │   │   ├── wounded_see_helper
        │   │   │   └── wounded_thanx
        │   │   ├── music
        │   │   ├── reactions
        │   │   │   ├── joke
        │   │   │   ├── music
        │   │   │   └── story
        │   │   ├── states
        │   │   │   ├── breath
        │   │   │   ├── idle
        │   │   │   ├── loot
        │   │   │   ├── meet
        │   │   │   ├── panic_human
        │   │   │   ├── panic_monster
        │   │   │   └── sleep
        │   │   ├── talk
        │   │   │   ├── intros
        │   │   │   ├── jokes
        │   │   │   └── use
        │   │   └── threat
        │   │       ├── back_off
        │   │       └── drop_weapon
        │   ├── csky
        │   │   ├── alife
        │   │   │   ├── attack
        │   │   │   ├── counter_attack
        │   │   │   ├── defence
        │   │   │   └── patrol
        │   │   ├── fight
        │   │   │   ├── attack
        │   │   │   ├── backup
        │   │   │   ├── cover_fire
        │   │   │   ├── death
        │   │   │   ├── detour
        │   │   │   ├── enemy
        │   │   │   ├── enemy_down
        │   │   │   ├── enemy_hit
        │   │   │   ├── fire
        │   │   │   ├── friend_hitted
        │   │   │   ├── friendly_fire
        │   │   │   ├── grenade
        │   │   │   ├── hit
        │   │   │   ├── post_combat_wait
        │   │   │   ├── searching_enemy
        │   │   │   ├── threat
        │   │   │   └── tolls
        │   │   ├── help
        │   │   │   ├── wounded
        │   │   │   ├── wounded_heavy
        │   │   │   └── wounded_thanx
        │   │   ├── music
        │   │   ├── reactions
        │   │   │   ├── box
        │   │   │   ├── joke
        │   │   │   ├── music
        │   │   │   └── story
        │   │   ├── states
        │   │   │   ├── breath
        │   │   │   ├── idle
        │   │   │   ├── meet
        │   │   │   ├── panic_human
        │   │   │   ├── panic_monster
        │   │   │   └── sleep
        │   │   ├── talk
        │   │   │   ├── intros
        │   │   │   ├── jokes
        │   │   │   └── use
        │   │   └── threat
        │   │       ├── back_off
        │   │       └── drop_weapon
        │   ├── dolg
        │   │   ├── alife
        │   │   │   ├── attack
        │   │   │   ├── counter_attack
        │   │   │   ├── defence
        │   │   │   └── patrol
        │   │   ├── fight
        │   │   │   ├── attack
        │   │   │   ├── backup
        │   │   │   ├── cover_fire
        │   │   │   ├── death
        │   │   │   ├── detour
        │   │   │   ├── enemy
        │   │   │   ├── enemy_down
        │   │   │   ├── enemy_hit
        │   │   │   ├── fire
        │   │   │   ├── friend_hitted
        │   │   │   ├── friendly_fire
        │   │   │   ├── friendly_grenade
        │   │   │   ├── grenade
        │   │   │   ├── hit
        │   │   │   ├── post_combat_wait
        │   │   │   ├── searching_enemy
        │   │   │   ├── threat
        │   │   │   └── tolls
        │   │   ├── hail
        │   │   ├── help
        │   │   │   ├── combat
        │   │   │   ├── not_wounded
        │   │   │   ├── wounded
        │   │   │   ├── wounded_heavy
        │   │   │   ├── wounded_not_see_helper
        │   │   │   ├── wounded_psy
        │   │   │   ├── wounded_see_helper
        │   │   │   └── wounded_thanx
        │   │   ├── music
        │   │   ├── reactions
        │   │   │   ├── box
        │   │   │   ├── joke
        │   │   │   ├── music
        │   │   │   └── story
        │   │   ├── states
        │   │   │   ├── breath
        │   │   │   ├── idle
        │   │   │   ├── loot
        │   │   │   ├── meet
        │   │   │   ├── panic_human
        │   │   │   ├── panic_monster
        │   │   │   ├── sleep
        │   │   │   └── trade
        │   │   ├── talk
        │   │   │   ├── intros
        │   │   │   ├── jokes
        │   │   │   └── use
        │   │   └── threat
        │   │       ├── back_off
        │   │       └── drop_weapon
        │   ├── freedom
        │   │   ├── alife
        │   │   │   ├── attack
        │   │   │   ├── counter_attack
        │   │   │   ├── defence
        │   │   │   └── patrol
        │   │   ├── fight
        │   │   │   ├── attack
        │   │   │   ├── backup
        │   │   │   ├── cover_fire
        │   │   │   ├── death
        │   │   │   ├── detour
        │   │   │   ├── enemy
        │   │   │   ├── enemy_down
        │   │   │   ├── enemy_hit
        │   │   │   ├── fire
        │   │   │   ├── friend_hitted
        │   │   │   ├── friendly_fire
        │   │   │   ├── friendly_grenade
        │   │   │   ├── grenade
        │   │   │   ├── hit
        │   │   │   ├── post_combat_wait
        │   │   │   ├── searching_enemy
        │   │   │   ├── threat
        │   │   │   └── tolls
        │   │   ├── hail
        │   │   ├── help
        │   │   │   ├── combat
        │   │   │   ├── not_wounded
        │   │   │   ├── wounded
        │   │   │   ├── wounded_heavy
        │   │   │   ├── wounded_not_see_helper
        │   │   │   ├── wounded_psy
        │   │   │   ├── wounded_see_helper
        │   │   │   └── wounded_thanx
        │   │   ├── music
        │   │   ├── reactions
        │   │   │   ├── box
        │   │   │   ├── joke
        │   │   │   ├── music
        │   │   │   └── story
        │   │   ├── states
        │   │   │   ├── breath
        │   │   │   ├── idle
        │   │   │   ├── loot
        │   │   │   ├── meet
        │   │   │   ├── panic_human
        │   │   │   ├── panic_monster
        │   │   │   ├── sleep
        │   │   │   └── trade
        │   │   ├── talk
        │   │   │   ├── intros
        │   │   │   ├── jokes
        │   │   │   └── use
        │   │   └── threat
        │   │       ├── back_off
        │   │       └── drop_weapon
        │   ├── killer
        │   │   ├── fight
        │   │   │   ├── attack
        │   │   │   ├── backup
        │   │   │   ├── cover_fire
        │   │   │   ├── danger_sound
        │   │   │   ├── death
        │   │   │   ├── detour
        │   │   │   ├── enemy
        │   │   │   ├── friend_hitted
        │   │   │   ├── friendly_fire
        │   │   │   ├── friendly_grenade
        │   │   │   ├── grenade
        │   │   │   ├── hit
        │   │   │   ├── searching_enemy
        │   │   │   └── tolls
        │   │   ├── hail
        │   │   ├── help
        │   │   │   ├── not_wounded
        │   │   │   ├── wounded
        │   │   │   ├── wounded_heavy
        │   │   │   │   └── aptechku
        │   │   │   ├── wounded_not_see_helper
        │   │   │   ├── wounded_psy
        │   │   │   ├── wounded_see_helper
        │   │   │   └── wounded_thanx
        │   │   ├── reactions
        │   │   │   ├── joke
        │   │   │   ├── music
        │   │   │   └── story
        │   │   ├── states
        │   │   │   ├── breath
        │   │   │   ├── idle
        │   │   │   ├── loot
        │   │   │   ├── panic_human
        │   │   │   ├── panic_monster
        │   │   │   └── sleep
        │   │   ├── talk
        │   │   │   ├── intros
        │   │   │   ├── jokes
        │   │   │   └── use
        │   │   └── threat
        │   │       ├── back_off
        │   │       └── drop_weapon
        │   ├── military
        │   │   ├── alife
        │   │   │   ├── attack
        │   │   │   ├── counter_attack
        │   │   │   └── patrol
        │   │   ├── fight
        │   │   │   ├── attack
        │   │   │   ├── backup
        │   │   │   ├── cover_fire
        │   │   │   ├── death
        │   │   │   ├── detour
        │   │   │   ├── enemy
        │   │   │   ├── enemy_down
        │   │   │   ├── enemy_hit
        │   │   │   ├── fire
        │   │   │   ├── friend_hitted
        │   │   │   ├── friendly_fire
        │   │   │   ├── grenade
        │   │   │   ├── hit
        │   │   │   ├── post_combat_wait
        │   │   │   ├── searching_enemy
        │   │   │   ├── threat
        │   │   │   └── tolls
        │   │   ├── hail
        │   │   ├── help
        │   │   │   ├── not_wounded
        │   │   │   ├── wounded
        │   │   │   ├── wounded_heavy
        │   │   │   ├── wounded_not_see_helper
        │   │   │   ├── wounded_psy
        │   │   │   ├── wounded_see_helper
        │   │   │   └── wounded_thanx
        │   │   ├── music
        │   │   ├── reactions
        │   │   │   ├── joke
        │   │   │   ├── music
        │   │   │   └── story
        │   │   ├── states
        │   │   │   ├── breath
        │   │   │   ├── idle
        │   │   │   ├── loot
        │   │   │   ├── meet
        │   │   │   ├── panic_human
        │   │   │   ├── panic_monster
        │   │   │   └── sleep
        │   │   ├── talk
        │   │   │   ├── intros
        │   │   │   ├── jokes
        │   │   │   └── use
        │   │   └── threat
        │   │       ├── back_off
        │   │       └── drop_weapon
        │   ├── monolith
        │   │   ├── fight
        │   │   │   ├── attack
        │   │   │   ├── backup
        │   │   │   ├── cover_fire
        │   │   │   ├── death
        │   │   │   ├── detour
        │   │   │   ├── enemy
        │   │   │   ├── enemy_down
        │   │   │   ├── enemy_hit
        │   │   │   ├── fire
        │   │   │   ├── friend_hitted
        │   │   │   ├── friendly_fire
        │   │   │   ├── grenade
        │   │   │   ├── hit
        │   │   │   ├── searching_enemy
        │   │   │   ├── threat
        │   │   │   └── tolls
        │   │   ├── help
        │   │   │   ├── wounded
        │   │   │   ├── wounded_heavy
        │   │   │   └── wounded_thanx
        │   │   ├── music
        │   │   ├── reactions
        │   │   │   ├── joke
        │   │   │   ├── music
        │   │   │   └── story
        │   │   ├── states
        │   │   │   ├── breath
        │   │   │   ├── idle
        │   │   │   ├── loot
        │   │   │   ├── panic_human
        │   │   │   ├── panic_monster
        │   │   │   └── sleep
        │   │   ├── talk
        │   │   │   ├── intros
        │   │   │   ├── jokes
        │   │   │   └── use
        │   │   └── threat
        │   │       ├── back_off
        │   │       └── drop_weapon
        │   ├── stalker
        │   │   ├── alife
        │   │   │   ├── attack
        │   │   │   ├── counter_attack
        │   │   │   ├── defence
        │   │   │   └── patrol
        │   │   ├── fight
        │   │   │   ├── attack
        │   │   │   ├── backup
        │   │   │   ├── cover_fire
        │   │   │   ├── death
        │   │   │   ├── detour
        │   │   │   ├── enemy
        │   │   │   ├── enemy_down
        │   │   │   ├── enemy_hit
        │   │   │   ├── fire
        │   │   │   ├── friend_hitted
        │   │   │   ├── friendly_fire
        │   │   │   ├── grenade
        │   │   │   ├── hit
        │   │   │   ├── post_combat_wait
        │   │   │   ├── searching_enemy
        │   │   │   ├── threat
        │   │   │   └── tolls
        │   │   ├── help
        │   │   │   ├── combat
        │   │   │   ├── wounded
        │   │   │   ├── wounded_heavy
        │   │   │   └── wounded_thanx
        │   │   ├── music
        │   │   ├── reactions
        │   │   │   ├── box
        │   │   │   ├── joke
        │   │   │   ├── music
        │   │   │   └── story
        │   │   ├── states
        │   │   │   ├── breath
        │   │   │   ├── idle
        │   │   │   ├── loot
        │   │   │   ├── meet
        │   │   │   ├── panic_human
        │   │   │   ├── panic_monster
        │   │   │   ├── sleep
        │   │   │   └── trade
        │   │   ├── talk
        │   │   │   ├── intros
        │   │   │   ├── jokes
        │   │   │   └── use
        │   │   └── threat
        │   │       ├── back_off
        │   │       └── drop_weapon
        │   └── zombied
        │       ├── fight
        │       │   ├── attack
        │       │   ├── death
        │       │   ├── enemy
        │       │   └── hit
        │       └── states
        │           ├── idle
        │           └── rising
        ├── human_03
        │   ├── bandit
        │   │   ├── alife
        │   │   │   ├── attack
        │   │   │   ├── counter_attack
        │   │   │   ├── defence
        │   │   │   └── patrol
        │   │   ├── fight
        │   │   │   ├── attack
        │   │   │   ├── backup
        │   │   │   ├── cover_fire
        │   │   │   ├── death
        │   │   │   ├── detour
        │   │   │   ├── enemy
        │   │   │   ├── friend_hitted
        │   │   │   ├── friendly_fire
        │   │   │   ├── grenade
        │   │   │   ├── hit
        │   │   │   ├── post_combat_wait
        │   │   │   ├── searching_enemy
        │   │   │   └── tolls
        │   │   ├── hail
        │   │   ├── help
        │   │   │   ├── not_wounded
        │   │   │   ├── wounded
        │   │   │   ├── wounded_heavy
        │   │   │   ├── wounded_not_see_helper
        │   │   │   ├── wounded_psy
        │   │   │   ├── wounded_see_helper
        │   │   │   └── wounded_thanx
        │   │   ├── music
        │   │   ├── reactions
        │   │   │   ├── joke
        │   │   │   ├── music
        │   │   │   └── story
        │   │   ├── states
        │   │   │   ├── breath
        │   │   │   ├── idle
        │   │   │   ├── loot
        │   │   │   ├── meet
        │   │   │   ├── panic_human
        │   │   │   ├── panic_monster
        │   │   │   └── sleep
        │   │   ├── talk
        │   │   │   ├── intros
        │   │   │   ├── jokes
        │   │   │   └── use
        │   │   └── threat
        │   │       ├── back_off
        │   │       └── drop_weapon
        │   ├── csky
        │   │   ├── alife
        │   │   │   ├── attack
        │   │   │   ├── counter_attack
        │   │   │   ├── defence
        │   │   │   └── patrol
        │   │   ├── fight
        │   │   │   ├── attack
        │   │   │   ├── backup
        │   │   │   ├── cover_fire
        │   │   │   ├── death
        │   │   │   ├── detour
        │   │   │   ├── enemy
        │   │   │   ├── enemy_down
        │   │   │   ├── enemy_hit
        │   │   │   ├── fire
        │   │   │   ├── friend_hitted
        │   │   │   ├── friendly_fire
        │   │   │   ├── grenade
        │   │   │   ├── hit
        │   │   │   ├── post_combat_wait
        │   │   │   ├── searching_enemy
        │   │   │   ├── threat
        │   │   │   └── tolls
        │   │   ├── hail
        │   │   ├── help
        │   │   │   ├── not_wounded
        │   │   │   ├── wounded
        │   │   │   ├── wounded_heavy
        │   │   │   ├── wounded_not_see_helper
        │   │   │   ├── wounded_psy
        │   │   │   ├── wounded_see_helper
        │   │   │   └── wounded_thanx
        │   │   ├── music
        │   │   ├── reactions
        │   │   │   ├── box
        │   │   │   ├── joke
        │   │   │   ├── music
        │   │   │   └── story
        │   │   ├── states
        │   │   │   ├── breath
        │   │   │   ├── idle
        │   │   │   ├── meet
        │   │   │   ├── panic_human
        │   │   │   ├── panic_monster
        │   │   │   └── sleep
        │   │   ├── talk
        │   │   │   ├── intros
        │   │   │   ├── jokes
        │   │   │   └── use
        │   │   └── threat
        │   │       ├── back_off
        │   │       └── drop_weapon
        │   ├── dolg
        │   │   ├── alife
        │   │   │   ├── attack
        │   │   │   ├── counter_attack
        │   │   │   ├── defence
        │   │   │   └── patrol
        │   │   ├── fight
        │   │   │   ├── attack
        │   │   │   ├── backup
        │   │   │   ├── cover_fire
        │   │   │   ├── death
        │   │   │   ├── detour
        │   │   │   ├── enemy
        │   │   │   ├── enemy_down
        │   │   │   ├── enemy_hit
        │   │   │   ├── fire
        │   │   │   ├── friend_hitted
        │   │   │   ├── friendly_fire
        │   │   │   ├── friendly_grenade
        │   │   │   ├── grenade
        │   │   │   ├── hit
        │   │   │   ├── post_combat_wait
        │   │   │   ├── searching_enemy
        │   │   │   ├── threat
        │   │   │   └── tolls
        │   │   ├── hail
        │   │   ├── help
        │   │   │   ├── combat
        │   │   │   ├── not_wounded
        │   │   │   ├── wounded
        │   │   │   ├── wounded_heavy
        │   │   │   ├── wounded_not_see_helper
        │   │   │   ├── wounded_psy
        │   │   │   ├── wounded_see_helper
        │   │   │   └── wounded_thanx
        │   │   ├── music
        │   │   ├── reactions
        │   │   │   ├── box
        │   │   │   ├── joke
        │   │   │   ├── music
        │   │   │   └── story
        │   │   ├── states
        │   │   │   ├── breath
        │   │   │   ├── idle
        │   │   │   ├── loot
        │   │   │   ├── meet
        │   │   │   ├── panic_human
        │   │   │   ├── panic_monster
        │   │   │   ├── sleep
        │   │   │   └── trade
        │   │   ├── talk
        │   │   │   ├── intros
        │   │   │   ├── jokes
        │   │   │   └── use
        │   │   └── threat
        │   │       ├── back_off
        │   │       └── drop_weapon
        │   ├── freedom
        │   │   ├── alife
        │   │   │   ├── attack
        │   │   │   ├── counter_attack
        │   │   │   ├── defence
        │   │   │   └── patrol
        │   │   ├── fight
        │   │   │   ├── attack
        │   │   │   ├── backup
        │   │   │   ├── cover_fire
        │   │   │   ├── death
        │   │   │   ├── detour
        │   │   │   ├── enemy
        │   │   │   ├── enemy_down
        │   │   │   ├── enemy_hit
        │   │   │   ├── fire
        │   │   │   ├── friend_hitted
        │   │   │   ├── friendly_fire
        │   │   │   ├── friendly_grenade
        │   │   │   ├── grenade
        │   │   │   ├── hit
        │   │   │   ├── post_combat_wait
        │   │   │   ├── searching_enemy
        │   │   │   ├── threat
        │   │   │   └── tolls
        │   │   ├── hail
        │   │   ├── help
        │   │   │   ├── combat
        │   │   │   ├── not_wounded
        │   │   │   ├── wounded
        │   │   │   ├── wounded_heavy
        │   │   │   ├── wounded_not_see_helper
        │   │   │   ├── wounded_psy
        │   │   │   ├── wounded_see_helper
        │   │   │   └── wounded_thanx
        │   │   ├── music
        │   │   ├── reactions
        │   │   │   ├── box
        │   │   │   ├── joke
        │   │   │   ├── music
        │   │   │   └── story
        │   │   ├── states
        │   │   │   ├── breath
        │   │   │   ├── idle
        │   │   │   ├── loot
        │   │   │   ├── meet
        │   │   │   ├── panic_human
        │   │   │   ├── panic_monster
        │   │   │   ├── sleep
        │   │   │   └── trade
        │   │   ├── talk
        │   │   │   ├── intros
        │   │   │   ├── jokes
        │   │   │   └── use
        │   │   └── threat
        │   │       ├── back_off
        │   │       └── drop_weapon
        │   ├── killer
        │   │   ├── fight
        │   │   │   ├── attack
        │   │   │   ├── backup
        │   │   │   ├── cover_fire
        │   │   │   ├── danger_sound
        │   │   │   ├── death
        │   │   │   ├── detour
        │   │   │   ├── enemy
        │   │   │   ├── friend_hitted
        │   │   │   ├── friendly_fire
        │   │   │   ├── friendly_grenade
        │   │   │   ├── grenade
        │   │   │   ├── hit
        │   │   │   ├── searching_enemy
        │   │   │   └── tolls
        │   │   ├── hail
        │   │   ├── help
        │   │   │   ├── not_wounded
        │   │   │   ├── wounded
        │   │   │   ├── wounded_heavy
        │   │   │   │   └── aptechku
        │   │   │   ├── wounded_not_see_helper
        │   │   │   ├── wounded_psy
        │   │   │   ├── wounded_see_helper
        │   │   │   └── wounded_thanx
        │   │   ├── reactions
        │   │   │   ├── joke
        │   │   │   ├── music
        │   │   │   └── story
        │   │   ├── states
        │   │   │   ├── breath
        │   │   │   ├── idle
        │   │   │   ├── loot
        │   │   │   ├── panic_human
        │   │   │   ├── panic_monster
        │   │   │   └── sleep
        │   │   ├── talk
        │   │   │   ├── intros
        │   │   │   ├── jokes
        │   │   │   └── use
        │   │   └── threat
        │   │       ├── back_off
        │   │       └── drop_weapon
        │   ├── military
        │   │   ├── alife
        │   │   │   ├── attack
        │   │   │   ├── counter_attack
        │   │   │   └── patrol
        │   │   ├── fight
        │   │   │   ├── attack
        │   │   │   ├── backup
        │   │   │   ├── cover_fire
        │   │   │   ├── death
        │   │   │   ├── detour
        │   │   │   ├── enemy
        │   │   │   ├── enemy_down
        │   │   │   ├── enemy_hit
        │   │   │   ├── fire
        │   │   │   ├── friend_hitted
        │   │   │   ├── friendly_fire
        │   │   │   ├── grenade
        │   │   │   ├── hit
        │   │   │   ├── post_combat_wait
        │   │   │   ├── searching_enemy
        │   │   │   ├── threat
        │   │   │   └── tolls
        │   │   ├── hail
        │   │   ├── help
        │   │   │   ├── not_wounded
        │   │   │   ├── wounded
        │   │   │   ├── wounded_heavy
        │   │   │   ├── wounded_not_see_helper
        │   │   │   ├── wounded_psy
        │   │   │   ├── wounded_see_helper
        │   │   │   └── wounded_thanx
        │   │   ├── music
        │   │   ├── reactions
        │   │   │   ├── joke
        │   │   │   ├── music
        │   │   │   └── story
        │   │   ├── states
        │   │   │   ├── breath
        │   │   │   ├── idle
        │   │   │   ├── loot
        │   │   │   ├── meet
        │   │   │   ├── panic_human
        │   │   │   ├── panic_monster
        │   │   │   └── sleep
        │   │   ├── talk
        │   │   │   ├── intros
        │   │   │   ├── jokes
        │   │   │   └── use
        │   │   └── threat
        │   │       ├── back_off
        │   │       └── drop_weapon
        │   ├── monolith
        │   │   ├── fight
        │   │   │   ├── attack
        │   │   │   ├── backup
        │   │   │   ├── cover_fire
        │   │   │   ├── death
        │   │   │   ├── detour
        │   │   │   ├── enemy
        │   │   │   ├── enemy_down
        │   │   │   ├── enemy_hit
        │   │   │   ├── fire
        │   │   │   ├── friend_hitted
        │   │   │   ├── friendly_fire
        │   │   │   ├── grenade
        │   │   │   ├── hit
        │   │   │   ├── searching_enemy
        │   │   │   ├── threat
        │   │   │   └── tolls
        │   │   ├── help
        │   │   │   ├── wounded
        │   │   │   ├── wounded_heavy
        │   │   │   └── wounded_thanx
        │   │   ├── music
        │   │   ├── reactions
        │   │   │   ├── joke
        │   │   │   ├── music
        │   │   │   └── story
        │   │   ├── states
        │   │   │   ├── breath
        │   │   │   ├── idle
        │   │   │   ├── loot
        │   │   │   ├── panic_human
        │   │   │   ├── panic_monster
        │   │   │   └── sleep
        │   │   ├── talk
        │   │   │   ├── intros
        │   │   │   ├── jokes
        │   │   │   └── use
        │   │   └── threat
        │   │       ├── back_off
        │   │       └── drop_weapon
        │   ├── stalker
        │   │   ├── alife
        │   │   │   ├── attack
        │   │   │   ├── counter_attack
        │   │   │   ├── defence
        │   │   │   └── patrol
        │   │   ├── fight
        │   │   │   ├── attack
        │   │   │   ├── backup
        │   │   │   ├── cover_fire
        │   │   │   ├── death
        │   │   │   ├── detour
        │   │   │   ├── enemy
        │   │   │   ├── enemy_down
        │   │   │   ├── enemy_hit
        │   │   │   ├── fire
        │   │   │   ├── friend_hitted
        │   │   │   ├── friendly_fire
        │   │   │   ├── grenade
        │   │   │   ├── hit
        │   │   │   ├── post_combat_wait
        │   │   │   ├── searching_enemy
        │   │   │   ├── threat
        │   │   │   └── tolls
        │   │   ├── hail
        │   │   ├── help
        │   │   │   ├── combat
        │   │   │   ├── not_wounded
        │   │   │   ├── wounded
        │   │   │   ├── wounded_heavy
        │   │   │   ├── wounded_not_see_helper
        │   │   │   ├── wounded_psy
        │   │   │   ├── wounded_see_helper
        │   │   │   └── wounded_thanx
        │   │   ├── music
        │   │   ├── reactions
        │   │   │   ├── box
        │   │   │   ├── joke
        │   │   │   ├── music
        │   │   │   └── story
        │   │   ├── script
        │   │   ├── states
        │   │   │   ├── breath
        │   │   │   ├── idle
        │   │   │   ├── loot
        │   │   │   ├── meet
        │   │   │   ├── panic_human
        │   │   │   ├── panic_monster
        │   │   │   ├── sleep
        │   │   │   └── trade
        │   │   ├── talk
        │   │   │   ├── intros
        │   │   │   ├── jokes
        │   │   │   └── use
        │   │   └── threat
        │   │       ├── back_off
        │   │       └── drop_weapon
        │   └── zombied
        │       ├── fight
        │       │   ├── attack
        │       │   ├── death
        │       │   ├── enemy
        │       │   └── hit
        │       └── states
        │           ├── idle
        │           └── rising
        ├── multiplayer
        │   ├── automatic
        │   ├── team_1
        │   └── team_2
        └── scenario
            ├── jupiter
            ├── pripyat
            ├── underpass
            └── zaton
```

<a id="xm"></a>

### xefis_movies.db

```console
├── configs
│   └── ui
├── sounds
│   └── music
└── textures
    ├── intro
    ├── outro
    └── ui
```

<a id="xe"></a>

### xenglish.db

```console
├── configs
│   └── text
│       └── eng
├── sounds
│   └── characters_voice
│       ├── human_01
│       │   ├── bandit
│       │   │   └── states
│       │   │       └── meet
│       │   ├── dolg
│       │   │   └── states
│       │   │       └── meet
│       │   ├── freedom
│       │   │   └── states
│       │   │       └── meet
│       │   ├── military
│       │   │   └── states
│       │   │       └── meet
│       │   └── stalker
│       │       └── states
│       │           └── meet
│       ├── human_02
│       │   ├── bandit
│       │   │   └── states
│       │   │       └── meet
│       │   ├── dolg
│       │   │   └── states
│       │   │       └── meet
│       │   ├── freedom
│       │   │   └── states
│       │   │       └── meet
│       │   ├── military
│       │   │   └── states
│       │   │       └── meet
│       │   └── stalker
│       │       └── states
│       │           └── meet
│       ├── human_03
│       │   ├── freedom
│       │   │   └── states
│       │   │       └── meet
│       │   ├── military
│       │   │   └── states
│       │   │       └── meet
│       │   └── stalker
│       │       ├── script
│       │       └── states
│       │           └── meet
│       ├── multiplayer
│       │   ├── automatic
│       │   ├── team_1
│       │   └── team_2
│       └── scenario
│           ├── jupiter
│           ├── pripyat
│           ├── underpass
│           └── zaton
└── textures
    └── ui
```

## patches - directory

<a id="xp02"></a>

### xpatch_02.db

```console
├── configs
│   ├── creatures
│   ├── gameplay
│   ├── misc
│   │   └── trade
│   ├── mp
│   │   └── weapons_mp
│   ├── scripts
│   │   ├── evac
│   │   ├── jupiter
│   │   │   └── anomaly
│   │   ├── labx8
│   │   ├── pripyat
│   │   ├── underpass
│   │   └── zaton
│   │       └── anomaly
│   ├── text
│   │   ├── cze
│   │   ├── eng
│   │   ├── fra
│   │   ├── ger
│   │   ├── ita
│   │   ├── map_desc
│   │   ├── pol
│   │   ├── rus
│   │   ├── spa
│   │   └── ukr
│   ├── ui
│   │   └── textures_descr
│   └── weapons
├── meshes
│   └── actors
├── scripts
├── shaders
│   ├── r1
│   │   └── objects
│   │       └── r1
│   │           ├── add_point.ps
│   │           ├── add_ppa.ps
│   │           ├── add_spot.ps
│   │           ├── avg2.ps
│   │           ├── avg4.ps
│   │           ├── base_lplanes.ps
│   │           ├── base_lplanes.vs
│   │           ├── clouds.ps
│   │           ├── clouds.vs
│   │           ├── detail.ps
│   │           ├── detail_still.vs
│   │           ├── detail_wave.vs
│   │           ├── editor.vs
│   │           ├── font2.ps
│   │           ├── hud3d.ps
│   │           ├── hud3d.vs
│   │           ├── hud_font.ps
│   │           ├── impl_dt.ps
│   │           ├── impl_dt.vs
│   │           ├── impl_l.ps
│   │           ├── impl_l.vs
│   │           ├── impl_point.vs
│   │           ├── impl.ps
│   │           ├── impl_spot.vs
│   │           ├── impl.vs
│   │           ├── lmap_dt.ps
│   │           ├── lmap_dt.vs
│   │           ├── lmape.ps
│   │           ├── lmape.vs
│   │           ├── lmap_l.ps
│   │           ├── lmap_l.vs
│   │           ├── lmap_point.vs
│   │           ├── lmap.ps
│   │           ├── lmap_spot.vs
│   │           ├── lmap.vs
│   │           ├── lod.ps
│   │           ├── lod.vs
│   │           ├── model_def_hq.ps
│   │           ├── model_def_hq.vs
│   │           ├── model_def_lplanes.vs
│   │           ├── model_def_lq.ps
│   │           ├── model_def_lqs.vs
│   │           ├── model_def_lq.vs
│   │           ├── model_def_point.vs
│   │           ├── model_def_shadow.vs
│   │           ├── model_def_spot.vs
│   │           ├── model_distort2t.vs
│   │           ├── model_distort4ghost.vs
│   │           ├── model_distort4glass.vs
│   │           ├── model_distort_inv.vs
│   │           ├── model_distort.vs
│   │           ├── model_env_hq.ps
│   │           ├── model_env_hq.vs
│   │           ├── model_env_lq.ps
│   │           ├── model_env_lq.vs
│   │           ├── model_env.ps
│   │           ├── model_env_sl.ps
│   │           ├── model_shadow.ps
│   │           ├── particle2t.ps
│   │           ├── particle_alphaonly.ps
│   │           ├── particle_distort.ps
│   │           ├── particle.ps
│   │           ├── particle.vs
│   │           ├── portal.vs
│   │           ├── postprocess_cm_pre.ps
│   │           ├── postprocess_d.ps
│   │           ├── postprocess.ps
│   │           ├── simple_color.ps
│   │           ├── simple_color.vs
│   │           ├── simple_point.vs
│   │           ├── simple.ps
│   │           ├── simple_spot.vs
│   │           ├── simple.vs
│   │           ├── sky2.ps
│   │           ├── sky2.vs
│   │           ├── sun2.ps
│   │           ├── tree_s_dt.vs
│   │           ├── tree_s_point.vs
│   │           ├── tree_s_spot.vs
│   │           ├── tree_s.vs
│   │           ├── tree_test.vs
│   │           ├── tree_wave_dt.vs
│   │           ├── tree_wave_point.vs
│   │           ├── tree_wave_spot.vs
│   │           ├── tree_wave.vs
│   │           ├── tree_w_dt.vs
│   │           ├── tree_w_point.vs
│   │           ├── tree_w_spot.vs
│   │           ├── tree_w.vs
│   │           ├── vert_dt.ps
│   │           ├── vert_dt.vs
│   │           ├── vert_l.ps
│   │           ├── vert_l.vs
│   │           ├── vert_point.vs
│   │           ├── vert.ps
│   │           ├── vert_spot.vs
│   │           ├── vert.vs
│   │           ├── waterd.ps
│   │           ├── waterd.vs
│   │           ├── water.ps
│   │           ├── water.vs
│   │           ├── wmarkmult.ps
│   │           ├── wmark_point.vs
│   │           ├── wmark_spot.vs
│   │           ├── wmark.vs
│   │           └── yuv2rgb.ps
│   ├── r2
│   └── r3
│       ├── dx11
│       └── objects
│           ├── r3
│           │   ├── accum_base.ps
│           │   ├── accum_emissivel.ps
│           │   ├── accum_emissive.ps
│           │   ├── accum_indirect_msaa.ps
│           │   ├── accum_indirect_nomsaa.ps
│           │   ├── accum_indirect.ps
│           │   ├── accum_mask.vs
│           │   ├── accum_omni_normal_msaa.ps
│           │   ├── accum_omni_normal_nomsaa.ps
│           │   ├── accum_omni_normal.ps
│           │   ├── accum_omni_transluent_msaa.ps
│           │   ├── accum_omni_transluent_nomsaa.ps
│           │   ├── accum_omni_transluent.ps
│           │   ├── accum_omni_unshadowed_msaa.ps
│           │   ├── accum_omni_unshadowed_nomsaa.ps
│           │   ├── accum_omni_unshadowed.ps
│           │   ├── accum_spot_fullsize_msaa.ps
│           │   ├── accum_spot_fullsize_nomsaa.ps
│           │   ├── accum_spot_fullsize.ps
│           │   ├── accum_spot_normal_msaa.ps
│           │   ├── accum_spot_normal_nomsaa.ps
│           │   ├── accum_spot_normal.ps
│           │   ├── accum_spot_unshadowed_msaa.ps
│           │   ├── accum_spot_unshadowed_nomsaa.ps
│           │   ├── accum_spot_unshadowed.ps
│           │   ├── accum_sun_far_msaa.ps
│           │   ├── accum_sun_far_nomsaa.ps
│           │   ├── accum_sun_far.ps
│           │   ├── accum_sun_mask_msaa.ps
│           │   ├── accum_sun_mask_nomsaa.ps
│           │   ├── accum_sun_mask.ps
│           │   ├── accum_sun_msaa.ps
│           │   ├── accum_sun_near_msaa_minmax.ps
│           │   ├── accum_sun_near_msaa_nominmax.ps
│           │   ├── accum_sun_near_msaa.ps
│           │   ├── accum_sun_near_nomsaa_minmax.ps
│           │   ├── accum_sun_near_nomsaa_nominmax.ps
│           │   ├── accum_sun_near_nomsaa.ps
│           │   ├── accum_sun_near_old.ps
│           │   ├── accum_sun_near.ps
│           │   ├── accum_sun_nomsaa.ps
│           │   ├── accum_sun.ps
│           │   ├── accum_sun.vs
│           │   ├── accum_volumetric_msaa.ps
│           │   ├── accum_volumetric_nomsaa.ps
│           │   ├── accum_volumetric_nomsaa.vs
│           │   ├── accum_volumetric.ps
│           │   ├── accum_volumetric_sun_minmax.ps
│           │   ├── accum_volumetric_sun_msaa0.ps
│           │   ├── accum_volumetric_sun_msaa1.ps
│           │   ├── accum_volumetric_sun_msaa2.ps
│           │   ├── accum_volumetric_sun_msaa3.ps
│           │   ├── accum_volumetric_sun_msaa4.ps
│           │   ├── accum_volumetric_sun_msaa5.ps
│           │   ├── accum_volumetric_sun_msaa6.ps
│           │   ├── accum_volumetric_sun_msaa7.ps
│           │   ├── accum_volumetric_sun_msaa.ps
│           │   ├── accum_volumetric_sun_nomsaa.ps
│           │   ├── accum_volumetric_sun.ps
│           │   ├── accum_volumetric.vs
│           │   ├── accum_volume.vs
│           │   ├── base_lplanes.ps
│           │   ├── base_lplanes.vs
│           │   ├── bloom_build.ps
│           │   ├── bloom_filter_f.ps
│           │   ├── bloom_filter.ps
│           │   ├── bloom_luminance_1.ps
│           │   ├── bloom_luminance_2.ps
│           │   ├── bloom_luminance_3.ps
│           │   ├── clouds.ps
│           │   ├── clouds.vs
│           │   ├── combine_1_msaa.ps
│           │   ├── combine_1_nomsaa.ps
│           │   ├── combine_1.ps
│           │   ├── combine_1.vs
│           │   ├── combine_2_aa_d.ps
│           │   ├── combine_2_aa.ps
│           │   ├── combine_2_naa_d.ps
│           │   ├── combine_2_naa.ps
│           │   ├── combine_volumetric.ps
│           │   ├── copy_msaa.ps
│           │   ├── copy_nomsaa.ps
│           │   ├── copy_p_msaa.ps
│           │   ├── copy_p_nomsaa.ps
│           │   ├── copy_p.ps
│           │   ├── copy.ps
│           │   ├── create_minmax_sm.ps
│           │   ├── deffer_base_aref_bump_db-hq.ps
│           │   ├── deffer_base_aref_bump_d-hq.ps
│           │   ├── deffer_base_aref_bump_d.ps
│           │   ├── deffer_base_aref_bump-hq.ps
│           │   ├── deffer_base_aref_bump.ps
│           │   ├── deffer_base_aref_flat_d.ps
│           │   ├── deffer_base_aref_flat.ps
│           │   ├── deffer_base_aref_steep_db-hq.ps
│           │   ├── deffer_base_aref_steep_d-hq.ps
│           │   ├── deffer_base_aref_steep-hq.ps
│           │   ├── deffer_base_atoc_aref_bump_db-hq.ps
│           │   ├── deffer_base_atoc_aref_bump_d-hq.ps
│           │   ├── deffer_base_atoc_aref_bump_d.ps
│           │   ├── deffer_base_atoc_aref_bump-hq.ps
│           │   ├── deffer_base_atoc_aref_bump.ps
│           │   ├── deffer_base_atoc_aref_flat_d.ps
│           │   ├── deffer_base_atoc_aref_flat.ps
│           │   ├── deffer_base_atoc_aref_steep_db-hq.ps
│           │   ├── deffer_base_atoc_aref_steep_d-hq.ps
│           │   ├── deffer_base_atoc_aref_steep-hq.ps
│           │   ├── deffer_base_atoc_lmh_aref_bump_db-hq.ps
│           │   ├── deffer_base_atoc_lmh_aref_bump_d-hq.ps
│           │   ├── deffer_base_atoc_lmh_aref_bump_d.ps
│           │   ├── deffer_base_atoc_lmh_aref_bump-hq.ps
│           │   ├── deffer_base_atoc_lmh_aref_bump.ps
│           │   ├── deffer_base_atoc_lmh_aref_flat_d.ps
│           │   ├── deffer_base_atoc_lmh_aref_flat.ps
│           │   ├── deffer_base_atoc_lmh_aref_steep_db-hq.ps
│           │   ├── deffer_base_atoc_lmh_aref_steep_d-hq.ps
│           │   ├── deffer_base_atoc_lmh_aref_steep-hq.ps
│           │   ├── deffer_base_bump_db-hq.ps
│           │   ├── deffer_base_bump_d-hq.ps
│           │   ├── deffer_base_bump_d-hq.vs
│           │   ├── deffer_base_bump_d.ps
│           │   ├── deffer_base_bump_d.vs
│           │   ├── deffer_base_bump-hq.ps
│           │   ├── deffer_base_bump-hq.vs
│           │   ├── deffer_base_bump.ps
│           │   ├── deffer_base_bump.vs
│           │   ├── deffer_base_flat_d.ps
│           │   ├── deffer_base_flat_d.vs
│           │   ├── deffer_base_flat.ps
│           │   ├── deffer_base_flat.vs
│           │   ├── deffer_base_lmh_aref_bump_db-hq.ps
│           │   ├── deffer_base_lmh_aref_bump_d-hq.ps
│           │   ├── deffer_base_lmh_aref_bump_d.ps
│           │   ├── deffer_base_lmh_aref_bump-hq.ps
│           │   ├── deffer_base_lmh_aref_bump.ps
│           │   ├── deffer_base_lmh_aref_flat_d.ps
│           │   ├── deffer_base_lmh_aref_flat.ps
│           │   ├── deffer_base_lmh_aref_steep_db-hq.ps
│           │   ├── deffer_base_lmh_aref_steep_d-hq.ps
│           │   ├── deffer_base_lmh_aref_steep-hq.ps
│           │   ├── deffer_base_lmh_bump_db-hq.ps
│           │   ├── deffer_base_lmh_bump_d-hq.ps
│           │   ├── deffer_base_lmh_bump_d-hq.vs
│           │   ├── deffer_base_lmh_bump_d.ps
│           │   ├── deffer_base_lmh_bump_d.vs
│           │   ├── deffer_base_lmh_bump-hq.ps
│           │   ├── deffer_base_lmh_bump-hq.vs
│           │   ├── deffer_base_lmh_bump.ps
│           │   ├── deffer_base_lmh_bump.vs
│           │   ├── deffer_base_lmh_flat_d.ps
│           │   ├── deffer_base_lmh_flat_d.vs
│           │   ├── deffer_base_lmh_flat.ps
│           │   ├── deffer_base_lmh_flat.vs
│           │   ├── deffer_base_lmh_steep_db-hq.ps
│           │   ├── deffer_base_lmh_steep_d-hq.ps
│           │   ├── deffer_base_lmh_steep-hq.ps
│           │   ├── deffer_base_steep_db-hq.ps
│           │   ├── deffer_base_steep_d-hq.ps
│           │   ├── deffer_base_steep-hq.ps
│           │   ├── deffer_detail_s_flat.vs
│           │   ├── deffer_detail_w_flat.vs
│           │   ├── deffer_impl_flat_d.ps
│           │   ├── deffer_impl_flat_d.vs
│           │   ├── deffer_impl_flat.ps
│           │   ├── deffer_model_bump_d-hq.vs
│           │   ├── deffer_model_bump_d.vs
│           │   ├── deffer_model_bump-hq.vs
│           │   ├── deffer_model_bump.vs
│           │   ├── deffer_model_flat_d.vs
│           │   ├── deffer_model_flat.vs
│           │   ├── deffer_particle.ps
│           │   ├── deffer_particle.vs
│           │   ├── deffer_tree_bump_d-hq.vs
│           │   ├── deffer_tree_bump_d.vs
│           │   ├── deffer_tree_bump-hq.vs
│           │   ├── deffer_tree_bump.vs
│           │   ├── deffer_tree_flat_d.vs
│           │   ├── deffer_tree_flat.vs
│           │   ├── deffer_tree_s_bump_d-hq.vs
│           │   ├── deffer_tree_s_bump_d.vs
│           │   ├── deffer_tree_s_bump-hq.vs
│           │   ├── deffer_tree_s_bump.vs
│           │   ├── deffer_tree_s_flat_d.vs
│           │   ├── deffer_tree_s_flat.vs
│           │   ├── depth_downs.ps
│           │   ├── distort.ps
│           │   ├── dumb.ps
│           │   ├── dumb.vs
│           │   ├── editor.vs
│           │   ├── effects_sun.vs
│           │   ├── effects_wallmark.vs
│           │   ├── fluid_advect_bfecc.ps
│           │   ├── fluid_advect_bfecc_temp.ps
│           │   ├── fluid_advect.ps
│           │   ├── fluid_advect_temp.ps
│           │   ├── fluid_advect_vel_g.ps
│           │   ├── fluid_advect_vel.ps
│           │   ├── fluid_array_dyn_oobb.gs
│           │   ├── fluid_array.gs
│           │   ├── fluid_array_oobb.gs
│           │   ├── fluid_confinement.ps
│           │   ├── fluid_divergence.ps
│           │   ├── fluid_edge_detect.ps
│           │   ├── fluid_edge_detect.vs
│           │   ├── fluid_gaussian.ps
│           │   ├── fluid_grid_dyn_oobb.vs
│           │   ├── fluid_grid_oobb.vs
│           │   ├── fluid_grid.vs
│           │   ├── fluid_jacobi.ps
│           │   ├── fluid_obst_dynamic_oobb.ps
│           │   ├── fluid_obst_static_oobb.ps
│           │   ├── fluid_project.ps
│           │   ├── fluid_raycastcopy_quad_fire.ps
│           │   ├── fluid_raycastcopy_quad.ps
│           │   ├── fluid_raycast_quad_fire.ps
│           │   ├── fluid_raycast_quad.ps
│           │   ├── fluid_raycast_quad.vs
│           │   ├── fluid_raydata_back.ps
│           │   ├── fluid_raydata_back.vs
│           │   ├── fluid_raydatacopy_quad.ps
│           │   ├── fluid_raydata_front.ps
│           │   ├── fluid_raydata_front.vs
│           │   ├── fluid_vorticity.ps
│           │   ├── font2.ps
│           │   ├── hud3d.ps
│           │   ├── hud3d.vs
│           │   ├── hud_crosshair.vs
│           │   ├── hud_font.ps
│           │   ├── lmape.ps
│           │   ├── lmape.vs
│           │   ├── lod.ps
│           │   ├── lod.vs
│           │   ├── mark_msaa_edges.ps
│           │   ├── model_def_lplanes.vs
│           │   ├── model_def_lq.ps
│           │   ├── model_def_lq.vs
│           │   ├── model_distort4ghost.vs
│           │   ├── model_distort4glass.vs
│           │   ├── model_distort_inv.vs
│           │   ├── model_distort.vs
│           │   ├── model_env_lq.ps
│           │   ├── model_env_lq.vs
│           │   ├── particle_alphaonly.ps
│           │   ├── particle-clip.vs
│           │   ├── particle_distort.ps
│           │   ├── particle_hard.ps
│           │   ├── particle.ps
│           │   ├── particle_s-aadd.ps
│           │   ├── particle_s-add.ps
│           │   ├── particle_s-blend.ps
│           │   ├── particle.vs
│           │   ├── portal.ps
│           │   ├── portal.vs
│           │   ├── postprocess_cm.ps
│           │   ├── postprocess.ps
│           │   ├── rain_apply_gloss_msaa.ps
│           │   ├── rain_apply_gloss_nomsaa.ps
│           │   ├── rain_apply_gloss.ps
│           │   ├── rain_apply_normal_msaa.ps
│           │   ├── rain_apply_normal_nomsaa.ps
│           │   ├── rain_apply_normal.ps
│           │   ├── rain_layer.ps
│           │   ├── rain_patch_normal_msaa.ps
│           │   ├── rain_patch_normal_new.ps
│           │   ├── rain_patch_normal_nomsaa.ps
│           │   ├── rain_patch_normal.ps
│           │   ├── shadow_direct_base_aref.ps
│           │   ├── shadow_direct_base_aref.vs
│           │   ├── shadow_direct_base.ps
│           │   ├── shadow_direct_base.vs
│           │   ├── shadow_direct_model_aref.vs
│           │   ├── shadow_direct_model.vs
│           │   ├── shadow_direct_tree_aref.vs
│           │   ├── shadow_direct_tree_s_aref.vs
│           │   ├── shadow_direct_tree_s.vs
│           │   ├── shadow_direct_tree.vs
│           │   ├── simple_color.ps
│           │   ├── simple.ps
│           │   ├── sky2.ps
│           │   ├── sky2.vs
│           │   ├── ssao_calc_msaa.ps
│           │   ├── ssao_calc_nomsaa.ps
│           │   ├── ssao_calc.ps
│           │   ├── stub_default_ma.ps
│           │   ├── stub_default.ps
│           │   ├── stub_default.vs
│           │   ├── stub_notransform_2uv.vs
│           │   ├── stub_notransform_aa_aa.vs
│           │   ├── stub_notransform_build.vs
│           │   ├── stub_notransform_filter.vs
│           │   ├── stub_notransform_postpr.vs
│           │   ├── stub_notransform_t_m2.vs
│           │   ├── stub_notransform_t_m4.vs
│           │   ├── stub_notransform_t_ma.vs
│           │   ├── stub_notransform_t.vs
│           │   ├── stub_notransform.vs
│           │   ├── test.gs
│           │   ├── vert.ps
│           │   ├── vert.vs
│           │   ├── waterd.ps
│           │   ├── waterd_soft.ps
│           │   ├── waterd_soft.vs
│           │   ├── waterd.vs
│           │   ├── water.ps
│           │   ├── water_soft.ps
│           │   ├── water_soft.vs
│           │   ├── water.vs
│           │   ├── wmark.vs
│           │   └── yuv2rgb.ps
│           └── r4
│               ├── accum_base.ps
│               ├── accum_emissivel.ps
│               ├── accum_emissive.ps
│               ├── accum_indirect_msaa.ps
│               ├── accum_indirect_nomsaa.ps
│               ├── accum_indirect.ps
│               ├── accum_mask.vs
│               ├── accum_omni_normal_msaa.ps
│               ├── accum_omni_normal_nomsaa.ps
│               ├── accum_omni_normal.ps
│               ├── accum_omni_transluent_msaa.ps
│               ├── accum_omni_transluent_nomsaa.ps
│               ├── accum_omni_transluent.ps
│               ├── accum_omni_unshadowed_msaa.ps
│               ├── accum_omni_unshadowed_nomsaa.ps
│               ├── accum_omni_unshadowed.ps
│               ├── accum_spot_fullsize_msaa.ps
│               ├── accum_spot_fullsize_nomsaa.ps
│               ├── accum_spot_fullsize.ps
│               ├── accum_spot_normal_msaa.ps
│               ├── accum_spot_normal_nomsaa.ps
│               ├── accum_spot_normal.ps
│               ├── accum_spot_unshadowed_msaa.ps
│               ├── accum_spot_unshadowed_nomsaa.ps
│               ├── accum_spot_unshadowed.ps
│               ├── accum_sun_far_msaa.ps
│               ├── accum_sun_far_nomsaa.ps
│               ├── accum_sun_far.ps
│               ├── accum_sun_mask_msaa.ps
│               ├── accum_sun_mask_nomsaa.ps
│               ├── accum_sun_mask.ps
│               ├── accum_sun_msaa.ps
│               ├── accum_sun_near_msaa_minmax.ps
│               ├── accum_sun_near_msaa_nominmax.ps
│               ├── accum_sun_near_msaa.ps
│               ├── accum_sun_near_nomsaa_minmax.ps
│               ├── accum_sun_near_nomsaa_nominmax.ps
│               ├── accum_sun_near_nomsaa.ps
│               ├── accum_sun_near_old.ps
│               ├── accum_sun_near.ps
│               ├── accum_sun_nomsaa.ps
│               ├── accum_sun.ps
│               ├── accum_sun.vs
│               ├── accum_volumetric_msaa.ps
│               ├── accum_volumetric_nomsaa.ps
│               ├── accum_volumetric_nomsaa.vs
│               ├── accum_volumetric.ps
│               ├── accum_volumetric_sun_minmax.ps
│               ├── accum_volumetric_sun_msaa0.ps
│               ├── accum_volumetric_sun_msaa1.ps
│               ├── accum_volumetric_sun_msaa2.ps
│               ├── accum_volumetric_sun_msaa3.ps
│               ├── accum_volumetric_sun_msaa4.ps
│               ├── accum_volumetric_sun_msaa5.ps
│               ├── accum_volumetric_sun_msaa6.ps
│               ├── accum_volumetric_sun_msaa7.ps
│               ├── accum_volumetric_sun_msaa.ps
│               ├── accum_volumetric_sun_nomsaa.ps
│               ├── accum_volumetric_sun.ps
│               ├── accum_volumetric.vs
│               ├── accum_volume.vs
│               ├── base_lplanes.ps
│               ├── base_lplanes.vs
│               ├── bloom_build.ps
│               ├── bloom_filter_f.ps
│               ├── bloom_filter.ps
│               ├── bloom_luminance_1.ps
│               ├── bloom_luminance_2.ps
│               ├── bloom_luminance_3.ps
│               ├── clouds.ps
│               ├── clouds.vs
│               ├── combine_1_msaa.ps
│               ├── combine_1_nomsaa.ps
│               ├── combine_1.ps
│               ├── combine_1.vs
│               ├── combine_2_aa_d.ps
│               ├── combine_2_aa.ps
│               ├── combine_2_naa_d.ps
│               ├── combine_2_naa.ps
│               ├── combine_volumetric.ps
│               ├── copy_msaa.ps
│               ├── copy_nomsaa.ps
│               ├── copy_p_msaa.ps
│               ├── copy_p_nomsaa.ps
│               ├── copy_p.ps
│               ├── copy.ps
│               ├── create_minmax_sm.ps
│               ├── deffer_base_aref_bump_db-hq.ps
│               ├── deffer_base_aref_bump_d-hq.ps
│               ├── deffer_base_aref_bump_d.ps
│               ├── deffer_base_aref_bump-hq.ps
│               ├── deffer_base_aref_bump.ps
│               ├── deffer_base_aref_flat_d.ps
│               ├── deffer_base_aref_flat.ps
│               ├── deffer_base_aref_steep_db-hq.ps
│               ├── deffer_base_aref_steep_d-hq.ps
│               ├── deffer_base_aref_steep-hq.ps
│               ├── deffer_base_atoc_aref_bump_db-hq.ps
│               ├── deffer_base_atoc_aref_bump_d-hq.ps
│               ├── deffer_base_atoc_aref_bump_d.ps
│               ├── deffer_base_atoc_aref_bump-hq.ps
│               ├── deffer_base_atoc_aref_bump.ps
│               ├── deffer_base_atoc_aref_flat_d.ps
│               ├── deffer_base_atoc_aref_flat.ps
│               ├── deffer_base_atoc_aref_steep_db-hq.ps
│               ├── deffer_base_atoc_aref_steep_d-hq.ps
│               ├── deffer_base_atoc_aref_steep-hq.ps
│               ├── deffer_base_atoc_lmh_aref_bump_db-hq.ps
│               ├── deffer_base_atoc_lmh_aref_bump_d-hq.ps
│               ├── deffer_base_atoc_lmh_aref_bump_d.ps
│               ├── deffer_base_atoc_lmh_aref_bump-hq.ps
│               ├── deffer_base_atoc_lmh_aref_bump.ps
│               ├── deffer_base_atoc_lmh_aref_flat_d.ps
│               ├── deffer_base_atoc_lmh_aref_flat.ps
│               ├── deffer_base_atoc_lmh_aref_steep_db-hq.ps
│               ├── deffer_base_atoc_lmh_aref_steep_d-hq.ps
│               ├── deffer_base_atoc_lmh_aref_steep-hq.ps
│               ├── deffer_base_bump_db-hq.ps
│               ├── deffer_base_bump_d-hq.ps
│               ├── deffer_base_bump_d-hq.vs
│               ├── deffer_base_bump_d.ps
│               ├── deffer_base_bump_d.vs
│               ├── deffer_base_bump-hq.ps
│               ├── deffer_base_bump-hq.vs
│               ├── deffer_base_bump.ps
│               ├── deffer_base_bump.vs
│               ├── deffer_base_flat_d.ps
│               ├── deffer_base_flat_d.vs
│               ├── deffer_base_flat.ps
│               ├── deffer_base_flat.vs
│               ├── deffer_base_lmh_aref_bump_db-hq.ps
│               ├── deffer_base_lmh_aref_bump_d-hq.ps
│               ├── deffer_base_lmh_aref_bump_d.ps
│               ├── deffer_base_lmh_aref_bump-hq.ps
│               ├── deffer_base_lmh_aref_bump.ps
│               ├── deffer_base_lmh_aref_flat_d.ps
│               ├── deffer_base_lmh_aref_flat.ps
│               ├── deffer_base_lmh_aref_steep_db-hq.ps
│               ├── deffer_base_lmh_aref_steep_d-hq.ps
│               ├── deffer_base_lmh_aref_steep-hq.ps
│               ├── deffer_base_lmh_bump_db-hq.ps
│               ├── deffer_base_lmh_bump_d-hq.ps
│               ├── deffer_base_lmh_bump_d-hq.vs
│               ├── deffer_base_lmh_bump_d.ps
│               ├── deffer_base_lmh_bump_d.vs
│               ├── deffer_base_lmh_bump-hq.ps
│               ├── deffer_base_lmh_bump-hq.vs
│               ├── deffer_base_lmh_bump.ps
│               ├── deffer_base_lmh_bump.vs
│               ├── deffer_base_lmh_flat_d.ps
│               ├── deffer_base_lmh_flat_d.vs
│               ├── deffer_base_lmh_flat.ps
│               ├── deffer_base_lmh_flat.vs
│               ├── deffer_base_lmh_steep_db-hq.ps
│               ├── deffer_base_lmh_steep_d-hq.ps
│               ├── deffer_base_lmh_steep-hq.ps
│               ├── deffer_base_steep_db-hq.ps
│               ├── deffer_base_steep_d-hq.ps
│               ├── deffer_base_steep-hq.ps
│               ├── deffer_detail_s_flat.vs
│               ├── deffer_detail_w_flat.vs
│               ├── deffer_impl_flat_d.ps
│               ├── deffer_impl_flat_d.vs
│               ├── deffer_impl_flat.ps
│               ├── deffer_model_bump_d-hq.vs
│               ├── deffer_model_bump_d.vs
│               ├── deffer_model_bump-hq.vs
│               ├── deffer_model_bump.vs
│               ├── deffer_model_flat_d.vs
│               ├── deffer_model_flat.vs
│               ├── deffer_particle.ps
│               ├── deffer_particle.vs
│               ├── deffer_tree_bump_d-hq.vs
│               ├── deffer_tree_bump_d.vs
│               ├── deffer_tree_bump-hq.vs
│               ├── deffer_tree_bump.vs
│               ├── deffer_tree_flat_d.vs
│               ├── deffer_tree_flat.vs
│               ├── deffer_tree_s_bump_d-hq.vs
│               ├── deffer_tree_s_bump_d.vs
│               ├── deffer_tree_s_bump-hq.vs
│               ├── deffer_tree_s_bump.vs
│               ├── deffer_tree_s_flat_d.vs
│               ├── deffer_tree_s_flat.vs
│               ├── depth_downs.ps
│               ├── distort.ps
│               ├── dumb.ps
│               ├── dumb.vs
│               ├── editor.vs
│               ├── effects_sun.vs
│               ├── effects_wallmark.vs
│               ├── fluid_advect_bfecc.ps
│               ├── fluid_advect_bfecc_temp.ps
│               ├── fluid_advect.ps
│               ├── fluid_advect_temp.ps
│               ├── fluid_advect_vel_g.ps
│               ├── fluid_advect_vel.ps
│               ├── fluid_array_dyn_oobb.gs
│               ├── fluid_array.gs
│               ├── fluid_array_oobb.gs
│               ├── fluid_confinement.ps
│               ├── fluid_divergence.ps
│               ├── fluid_edge_detect.ps
│               ├── fluid_edge_detect.vs
│               ├── fluid_gaussian.ps
│               ├── fluid_grid_dyn_oobb.vs
│               ├── fluid_grid_oobb.vs
│               ├── fluid_grid.vs
│               ├── fluid_jacobi.ps
│               ├── fluid_obst_dynamic_oobb.ps
│               ├── fluid_obst_static_oobb.ps
│               ├── fluid_project.ps
│               ├── fluid_raycastcopy_quad_fire.ps
│               ├── fluid_raycastcopy_quad.ps
│               ├── fluid_raycast_quad_fire.ps
│               ├── fluid_raycast_quad.ps
│               ├── fluid_raycast_quad.vs
│               ├── fluid_raydata_back.ps
│               ├── fluid_raydata_back.vs
│               ├── fluid_raydatacopy_quad.ps
│               ├── fluid_raydata_front.ps
│               ├── fluid_raydata_front.vs
│               ├── fluid_vorticity.ps
│               ├── font2.ps
│               ├── hud3d.ps
│               ├── hud3d.vs
│               ├── hud_crosshair.vs
│               ├── hud_font.ps
│               ├── lmape.ps
│               ├── lmape.vs
│               ├── lod.ps
│               ├── lod.vs
│               ├── mark_msaa_edges.ps
│               ├── model_def_lplanes.vs
│               ├── model_def_lq.ps
│               ├── model_def_lq.vs
│               ├── model_distort4ghost.vs
│               ├── model_distort4glass.vs
│               ├── model_distort_inv.vs
│               ├── model_distort.vs
│               ├── model_env_lq.ps
│               ├── model_env_lq.vs
│               ├── particle_alphaonly.ps
│               ├── particle-clip.vs
│               ├── particle_distort.ps
│               ├── particle_hard.ps
│               ├── particle.ps
│               ├── particle_s-aadd.ps
│               ├── particle_s-add.ps
│               ├── particle_s-blend.ps
│               ├── particle.vs
│               ├── portal.ps
│               ├── portal.vs
│               ├── postprocess_cm.ps
│               ├── postprocess.ps
│               ├── rain_apply_gloss_msaa.ps
│               ├── rain_apply_gloss_nomsaa.ps
│               ├── rain_apply_gloss.ps
│               ├── rain_apply_normal_msaa.ps
│               ├── rain_apply_normal_nomsaa.ps
│               ├── rain_apply_normal.ps
│               ├── rain_layer.ps
│               ├── rain_patch_normal_msaa.ps
│               ├── rain_patch_normal_new.ps
│               ├── rain_patch_normal_nomsaa.ps
│               ├── rain_patch_normal.ps
│               ├── shadow_direct_base_aref.ps
│               ├── shadow_direct_base_aref.vs
│               ├── shadow_direct_base.ps
│               ├── shadow_direct_base.vs
│               ├── shadow_direct_model_aref.vs
│               ├── shadow_direct_model.vs
│               ├── shadow_direct_tree_aref.vs
│               ├── shadow_direct_tree_s_aref.vs
│               ├── shadow_direct_tree_s.vs
│               ├── shadow_direct_tree.vs
│               ├── simple_color.ps
│               ├── simple.ps
│               ├── sky2.ps
│               ├── sky2.vs
│               ├── ssao_calc_msaa.ps
│               ├── ssao_calc_nomsaa.ps
│               ├── ssao_calc.ps
│               ├── ssao_hdao.cs
│               ├── ssao_hdao_msaa.cs
│               ├── stub_default_ma.ps
│               ├── stub_default.ps
│               ├── stub_default.vs
│               ├── stub_notransform_2uv.vs
│               ├── stub_notransform_aa_aa.vs
│               ├── stub_notransform_build.vs
│               ├── stub_notransform_filter.vs
│               ├── stub_notransform_postpr.vs
│               ├── stub_notransform_t_m2.vs
│               ├── stub_notransform_t_m4.vs
│               ├── stub_notransform_t_ma.vs
│               ├── stub_notransform_t.vs
│               ├── stub_notransform.vs
│               ├── tess.ds
│               ├── tess.hs
│               ├── tess_shadow.ds
│               ├── test.gs
│               ├── vert.ps
│               ├── vert.vs
│               ├── waterd.ps
│               ├── waterd_soft.ps
│               ├── waterd_soft.vs
│               ├── waterd.vs
│               ├── water.ps
│               ├── water_soft.ps
│               ├── water_soft.vs
│               ├── water.vs
│               ├── wmark.vs
│               └── yuv2rgb.ps
├── sounds
│   └── music
└── textures
    └── ui
```

## resources - directory

<a id="cf"></a>

### configs.db

```console
├── ai
│   ├── alife
│   └── common
├── anims
│   ├── benchmarks
│   ├── camera_effects
│   │   ├── actor_move
│   │   ├── scenario_cam
│   │   │   ├── jupiter
│   │   │   ├── pripyat
│   │   │   └── zaton
│   │   └── weapon
│   └── helicopter
├── configs
│   ├── creatures
│   ├── environment
│   │   ├── ambients
│   │   ├── fog
│   │   ├── weather_effects
│   │   └── weathers
│   ├── gameplay
│   ├── misc
│   │   ├── outfit_upgrades
│   │   └── trade
│   ├── models
│   │   ├── capture
│   │   ├── objects
│   │   ├── vehicles
│   │   └── weapons
│   ├── mp
│   │   ├── soundmessages
│   │   └── weapons_mp
│   ├── prefetch
│   ├── scripts
│   │   ├── evac
│   │   │   └── smart
│   │   ├── jupiter
│   │   │   ├── anomaly
│   │   │   └── smart
│   │   ├── labx8
│   │   ├── pripyat
│   │   │   ├── anomaly
│   │   │   └── smart
│   │   ├── underpass
│   │   │   └── smart
│   │   └── zaton
│   │       ├── anomaly
│   │       └── smart
│   ├── text
│   │   └── map_desc
│   ├── ui
│   │   └── textures_descr
│   ├── weapons
│   │   └── upgrades
│   ├── weathers
│   └── zones
├── scripts
└── spawns
```

<a id="rs0"></a>

### resources.db0

```console
├── ai
├── anims
├── configs
├── levels
├── meshes
│   ├── actors
│   │   ├── stalker_bandit
│   │   ├── stalker_dolg
│   │   ├── stalker_freedom
│   │   ├── stalker_hero
│   │   ├── stalker_lesnik
│   │   ├── stalker_merc
│   │   ├── stalker_monolith
│   │   ├── stalker_mp
│   │   ├── stalker_nebo
│   │   ├── stalker_neutral
│   │   ├── stalker_soldier
│   │   ├── stalker_trader
│   │   ├── stalker_ucheniy
│   │   └── stalker_zombied
│   ├── dm
│   ├── dynamics
│   │   ├── anomaly
│   │   ├── armory_room
│   │   ├── artefacts
│   │   ├── balon
│   │   ├── box
│   │   │   └── part
│   │   ├── dead_body
│   │   ├── devices
│   │   │   ├── dev_antirad
│   │   │   ├── dev_aptechka
│   │   │   ├── dev_artefact
│   │   │   ├── dev_bandage
│   │   │   ├── dev_binoculars
│   │   │   ├── dev_bolt
│   │   │   ├── dev_bred
│   │   │   ├── dev_conserv
│   │   │   ├── dev_datchik_1
│   │   │   ├── dev_datchik_2
│   │   │   ├── dev_datchik_3
│   │   │   ├── dev_decoder
│   │   │   ├── dev_detector_1
│   │   │   ├── dev_detector_2
│   │   │   ├── dev_detector_3
│   │   │   ├── dev_detector_4
│   │   │   ├── dev_drink_stalker
│   │   │   ├── dev_flare
│   │   │   ├── dev_flash_1
│   │   │   ├── dev_flash_2
│   │   │   ├── dev_fmradio
│   │   │   ├── dev_guitar
│   │   │   ├── dev_harmonica
│   │   │   ├── dev_instrument_1
│   │   │   ├── dev_kolbasa
│   │   │   ├── dev_merger
│   │   │   ├── dev_pda
│   │   │   ├── dev_rukzak
│   │   │   ├── dev_torch_light
│   │   │   └── dev_vodka
│   │   ├── door
│   │   │   └── part
│   │   ├── el_tehnika
│   │   ├── equipment_cache
│   │   ├── equipments
│   │   │   ├── medical
│   │   │   └── quest
│   │   ├── fence
│   │   │   └── part
│   │   ├── firestation
│   │   ├── kitchen_room
│   │   │   └── part
│   │   ├── light
│   │   ├── medical_object
│   │   ├── outfit
│   │   ├── scene_objects
│   │   │   ├── darkvalley
│   │   │   ├── hospital
│   │   │   │   └── part
│   │   │   ├── labx8
│   │   │   ├── part
│   │   │   ├── pripyat
│   │   │   │   └── part
│   │   │   └── red_forest
│   │   ├── stul
│   │   ├── test_character
│   │   ├── vehicles
│   │   │   ├── btr
│   │   │   ├── mi2
│   │   │   │   └── part
│   │   │   └── mi24
│   │   │       └── part
│   │   ├── weapons
│   │   │   ├── wpn_abakan
│   │   │   ├── wpn_ak74
│   │   │   ├── wpn_ak74u
│   │   │   ├── wpn_ammo
│   │   │   ├── wpn_artefact
│   │   │   ├── wpn_beretta92fs
│   │   │   ├── wpn_bm16
│   │   │   ├── wpn_colt1911
│   │   │   ├── wpn_desert_eagle
│   │   │   ├── wpn_fn2000
│   │   │   ├── wpn_fort
│   │   │   ├── wpn_g36
│   │   │   ├── wpn_gauss
│   │   │   ├── wpn_grenades
│   │   │   ├── wpn_groza
│   │   │   ├── wpn_hand
│   │   │   ├── wpn_hpsa
│   │   │   ├── wpn_knife
│   │   │   ├── wpn_l85
│   │   │   ├── wpn_lr300
│   │   │   ├── wpn_mounted
│   │   │   ├── wpn_mp5
│   │   │   ├── wpn_pb
│   │   │   ├── wpn_pkm
│   │   │   ├── wpn_pm
│   │   │   ├── wpn_protecta
│   │   │   ├── wpn_rg6
│   │   │   ├── wpn_rpg7
│   │   │   ├── wpn_sig220
│   │   │   ├── wpn_sig550
│   │   │   ├── wpn_spas12
│   │   │   ├── wpn_svd
│   │   │   ├── wpn_svu
│   │   │   ├── wpn_toz34
│   │   │   ├── wpn_upgrade
│   │   │   ├── wpn_usp45
│   │   │   ├── wpn_val
│   │   │   ├── wpn_vintorez
│   │   │   ├── wpn_walter99
│   │   │   └── wpn_winchester1300
│   │   ├── wood_doski
│   │   └── workshop_room
│   └── monsters
│       ├── burer
│       ├── chimera
│       ├── controller
│       ├── crow
│       ├── dog
│       ├── flesh
│       ├── krovosos
│       ├── mutant_boar
│       ├── phantom
│       ├── poltergeist
│       ├── pseudodog
│       ├── psevdogigant
│       ├── rat
│       ├── snork
│       └── tushkano
├── scripts
├── shaders
│   ├── r1
│   │   ├── old
│   │   ├── shared
│   │   └── test
│   ├── r2
│   │   ├── shared
│   │   └── test
│   ├── r3
│   │   ├── dx11
│   │   └── shared
│   └── shared
├── sounds
│   ├── actor
│   ├── affects
│   ├── ambient
│   │   ├── arena
│   │   ├── background
│   │   ├── bar
│   │   ├── indoors
│   │   ├── jupiter
│   │   ├── labx8
│   │   ├── megaphones
│   │   ├── mine
│   │   ├── old
│   │   ├── outdoors
│   │   ├── pripyat
│   │   ├── random
│   │   ├── rnd_outdoor
│   │   ├── source.tmp
│   │   ├── special
│   │   ├── underground
│   │   ├── underpass
│   │   ├── x16
│   │   ├── x18
│   │   └── zaton
│   ├── anomaly
│   ├── car
│   ├── detectors
│   ├── device
│   │   ├── bridge
│   │   └── pda
│   ├── heart
│   ├── interface
│   ├── intro
│   ├── material
│   │   ├── actor
│   │   │   └── step
│   │   ├── barrel
│   │   │   └── collide
│   │   ├── bottle
│   │   │   └── collide
│   │   ├── bullet
│   │   │   └── collide
│   │   ├── dead-body
│   │   │   └── collide
│   │   ├── glass
│   │   ├── hoof
│   │   │   └── step
│   │   ├── human
│   │   │   ├── collide
│   │   │   └── step
│   │   ├── large
│   │   ├── large_furniture
│   │   ├── large_metal_trash
│   │   │   └── collide
│   │   ├── large-weapon
│   │   │   └── collide
│   │   ├── medium
│   │   ├── metal_box
│   │   │   └── collide
│   │   ├── small-weapon
│   │   │   └── collide
│   │   └── wood
│   ├── monsters
│   │   ├── biting
│   │   ├── bloodsucker
│   │   │   └── bak
│   │   ├── boar
│   │   ├── burer
│   │   ├── chimera
│   │   ├── controller
│   │   ├── crow
│   │   ├── dog
│   │   ├── flesh
│   │   │   └── bak
│   │   ├── giant
│   │   │   └── bak
│   │   ├── human
│   │   │   └── combat
│   │   │       ├── rus
│   │   │       ├── ukr
│   │   │       │   ├── alarm
│   │   │       │   ├── attack
│   │   │       │   ├── backup
│   │   │       │   ├── detour
│   │   │       │   ├── old
│   │   │       │   └── search
│   │   │       └── ukr2
│   │   ├── poltergeist
│   │   ├── pseudodog
│   │   ├── rat
│   │   │   └── old
│   │   ├── seller
│   │   ├── snork
│   │   ├── soldier
│   │   │   ├── blockpost
│   │   │   ├── commander
│   │   │   ├── injured
│   │   │   ├── radio
│   │   │   ├── radiocommandersoldier
│   │   │   ├── radiocommanderstalker
│   │   │   ├── radiovoice
│   │   │   └── soldiervoice
│   │   ├── stalker
│   │   │   ├── alarm
│   │   │   ├── combat
│   │   │   ├── copy
│   │   │   │   ├── copycopy
│   │   │   │   │   ├── alarm
│   │   │   │   │   ├── death
│   │   │   │   │   ├── humming
│   │   │   │   │   ├── surrender
│   │   │   │   │   └── wound
│   │   │   │   ├── default
│   │   │   │   │   ├── alarm
│   │   │   │   │   ├── death
│   │   │   │   │   ├── humming
│   │   │   │   │   ├── surrender
│   │   │   │   │   └── wound
│   │   │   │   ├── frodo
│   │   │   │   │   ├── alarm
│   │   │   │   │   ├── death
│   │   │   │   │   ├── humming
│   │   │   │   │   ├── surrender
│   │   │   │   │   └── wound
│   │   │   │   ├── koan
│   │   │   │   │   ├── alarm
│   │   │   │   │   ├── death
│   │   │   │   │   ├── humming
│   │   │   │   │   ├── surrender
│   │   │   │   │   └── wound
│   │   │   │   └── prof
│   │   │   │       ├── alarm
│   │   │   │       ├── death
│   │   │   │       ├── humming
│   │   │   │       ├── surrender
│   │   │   │       └── wound
│   │   │   ├── death
│   │   │   ├── hiccup
│   │   │   ├── humming
│   │   │   ├── surrender
│   │   │   └── wound
│   │   ├── tushkano
│   │   ├── zombie
│   │   │   ├── attack
│   │   │   ├── death
│   │   │   ├── hit
│   │   │   ├── idle
│   │   │   ├── notice
│   │   │   ├── pursuit
│   │   │   └── resurrect
│   │   └── zomby
│   ├── mp_actor
│   ├── music
│   │   └── combat
│   ├── nature
│   ├── test
│   ├── vehicles
│   │   └── helicopter
│   ├── video
│   └── weapons
├── spawns
└── textures
    ├── act
    ├── artifact
    ├── award
    ├── briks
    ├── controller
    ├── crete
    ├── decal
    ├── detail
    ├── door
    ├── ed
    ├── editor
    ├── floor
    ├── fx
    ├── glas
    ├── glass
    ├── glow
    ├── grad
    ├── grnd
    ├── internal
    ├── intro
    ├── item
    ├── lights
    ├── map
    ├── mtl
    ├── outro
    ├── pfx
    ├── prop
    ├── roof
    ├── sign
    ├── sky
    ├── staff
    ├── terrain
    ├── tile
    ├── trees
    ├── ui
    ├── veh
    ├── vine
    ├── wall
    ├── water
    ├── wind
    ├── wm
    ├── wood
    └── wpn
```

<a id="rs1"></a>

### resources.db1

```console
└── textures
    ├── act
    ├── artifact
    ├── award
    ├── briks
    ├── controller
    ├── crete
    ├── decal
    ├── detail
    ├── door
    ├── ed
    ├── editor
    ├── floor
    ├── fx
    ├── glas
    ├── glass
    ├── glow
    ├── grad
    ├── grnd
    ├── internal
    └── intro
```

<a id="rs2"></a>

### resources.db2

```console
└── textures
    ├── intro
    ├── item
    ├── lights
    ├── map
    ├── mtl
    └── outro
```

<a id="rs3"></a>

### resources.db3

```console
└── textures
    ├── outro
    ├── pfx
    ├── prop
    ├── roof
    ├── sign
    ├── sky
    ├── staff
    ├── terrain
    ├── tile
    ├── trees
    ├── ui
    └── veh
```

<a id="rs4"></a>

### resources.db4

```console
└── textures
    ├── veh
    ├── vine
    ├── wall
    ├── water
    ├── wind
    ├── wm
    ├── wood
    └── wpn
```
