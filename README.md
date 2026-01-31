
```python
tag = input("🔥Yo homie, what you tryna know 'bout me?👑").lower()

match tag:
    case "field":
        print("🌐 Field: Search | Ads | Recommendation | AI")

    case "tech":
        print("💻 Tech: Computer Science | Software Engineer | Distributed Systems")

    case "product":
        print("📊 Product: Demand | Value | Consensus | Model")

    case "vocal":
        print("🎤 Vocal: EVT | IVA | CVT")

    case "psychology":
        print("🧠 Psychology: Social Psychology | Negotiation | Game Theory")

    case "investment":
        print("📈 Investment: YONGPING DUAN | Warren Buffett")

    case _:
        print("🎵 Doctor, Actor, Lawyer, or a Singer ~\n
               🎵 Why not President, Be a dreamer ~\n
               ✨ I can be just the one I wanna be ~")
