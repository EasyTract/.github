```
███████╗ █████╗ ███████╗██╗   ██╗████████╗██████╗  █████╗  ██████╗████████╗
██╔════╝██╔══██╗██╔════╝╚██╗ ██╔╝╚══██╔══╝██╔══██╗██╔══██╗██╔════╝╚══██╔══╝
█████╗  ███████║███████╗ ╚████╔╝    ██║   ██████╔╝███████║██║        ██║
██╔══╝  ██╔══██║╚════██║  ╚██╔╝     ██║   ██╔══██╗██╔══██║██║        ██║
███████╗██║  ██║███████║   ██║      ██║   ██║  ██║██║  ██║╚██████╗   ██║
╚══════╝╚═╝  ╚═╝╚══════╝   ╚═╝      ╚═╝   ╚═╝  ╚═╝╚═╝  ╚═╝ ╚═════╝   ╚═╝
```

<div align="center">

### Eyes on every vehicle. Every time.

**EasyTract uses AI vision to automate aftermarket part detection in car wash tunnels before contact — increasing throughput and retract consistency while reducing vehicle damage.**

<br>

![Computer Vision](https://img.shields.io/badge/computer_vision-000000?style=for-the-badge&logo=opencv&logoColor=white)
![Python](https://img.shields.io/badge/python-000000?style=for-the-badge&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/pytorch-000000?style=for-the-badge&logo=pytorch&logoColor=white)
![Django](https://img.shields.io/badge/django-000000?style=for-the-badge&logo=django&logoColor=white)
![NVIDIA](https://img.shields.io/badge/on--site_inference-000000?style=for-the-badge&logo=nvidia&logoColor=white)

</div>

---

## The problem

A tunnel car wash moves a vehicle every few seconds, all day, in every kind of weather. Somewhere in that line is a vehicle carrying something the tunnel was never built to touch. The equipment has to move out of the way — and the only thing standing between that vehicle and a damage claim is a person who has been watching cars go by since 7 a.m.

People are good at this. People are not *consistently* good at this. Consistency is the whole game.

## What we built

```
   ┌─────────┐        ┌──────────────┐        ┌───────────┐        ┌────────┐
   │ vehicle │──────▶ │   detect &   │──────▶ │  operator │──────▶ │ retract│
   │  enters │        │    track     │        │  confirms │        │  fires │
   └─────────┘        └──────────────┘        └───────────┘        └────────┘
                       milliseconds             one glance          in time
```

A camera at the entry. A model that watches every pass, tracks each vehicle as a single unit through the tunnel, and surfaces what it sees before that vehicle reaches anything that moves.

Then it hands the decision to a human.

## Human in the loop, on purpose

**Nothing fires without a person confirming it.**

That isn't a limitation we plan to engineer away. It's the design. The system's job is to make sure the operator is never the first one to notice — not to replace the operator's judgment. Fast, tireless attention paired with human accountability beats either one alone, and it keeps the liability story honest.

## Where we are

```
[■■■■■■■■■■] core detection pipeline
[■■■■■■■■□□] live tunnel inference
[■■■■■□□□□□] operator interface
[■■■□□□□□□□] pilot deployment
[■□□□□□□□□□] multi-site
```

Actively in development. Building toward pilot installs with tunnel operators.

## Repositories

Our work is private while patent questions are open. If you're a wash operator, an investor, or someone who thinks a lot about vehicles and the machines that touch them, we're happy to talk.

<div align="center">
<br>

**Built by two people who thought this was a solvable problem.**

<sub>Noah Shewell · Grant Gatch</sub>

<br>

`Salt Lake City, Utah`

</div>
