# Architecture Overview

HDPE follows a strict layered architecture:

- GUI Layer: User interaction only
- Core Library: All logic and decision-making
- Server Layer: Compatibility and generation authority

The GUI has no access to:
- Encoding logic
- Compatibility rules
- Validation outcomes beyond success/failure
