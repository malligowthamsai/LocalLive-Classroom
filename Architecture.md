
---

# 🧠 4. Add an Architecture File (docs/architecture.md)

```markdown
# Architecture Overview

## Components

### 1. Admin Device (Professor)
- Captures video/audio
- Encodes stream
- Broadcasts over LAN

### 2. Student Devices
- Connect to same network
- Receive stream
- Decode and display

## Communication

- Peer-to-peer (WebRTC preferred)
- Or server-based relay (Node.js)

## Data Flow

Capture → Encode → Transmit → Decode → Display
