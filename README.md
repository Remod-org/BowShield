# BowShield for Rust

Enables holding your shield when using a bow or jackhammer.


## Configuration
```
{
  "Options": {
    "Held items that can use shield": [
      "bow_hunting",
      "jackhammer"
    ],
    "Block time": 30.0,
    "Damage mitigation factor": 1.0,
    "debug": false
  },
  "Version": {
    "Major": 0,
    "Minor": 0,
    "Patch": 2
  }
}
```

For "Held items that can use shield", you can try other held items - ymmv.

Currently, "Block time" has no impact.  Damage mitigation may - set to 1 to give 100% protection.
