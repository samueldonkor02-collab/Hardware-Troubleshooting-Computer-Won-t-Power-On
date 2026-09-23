# Hardware-Troubleshooting-Computer-Won-t-Power-On
This one's a scenario-based exercise rather than a hands-on lab: I'm playing IT technician working a ticket where a user's computer won't turn on at all, and walking through it using the standard six-step troubleshooting methodology instead of just guessing at fixes.

# Hardware Troubleshooting: Computer Won't Power On

`Troubleshooting Methodology` `Hardware` `PSU` `IT Support` `Ticketing`

## Overview

This one's a scenario-based exercise rather than a hands-on lab: I'm playing IT technician working a ticket where a user's computer won't turn on at all, and walking through it using the standard six-step troubleshooting methodology instead of just guessing at fixes.

## Objective

Practice applying a structured troubleshooting process (identify, theorize, test, act, verify, document) to a no-power hardware issue, and show the reasoning at each step rather than jumping straight to "replace the part."

## Scenario

A user submits a ticket saying their computer won't switch on. No other details up front, that's what step one is for.

## Troubleshooting Methodology

### 1. Identify the Problem

I start by talking to the user, not the machine. When did this start? Any recent changes, like a power outage, new hardware, or anything moved or unplugged? Then I look at the machine itself: do any lights come on, do the fans spin, any beep codes when the power button is pressed?

**Observation:** The computer is completely unresponsive when the power button is pressed. No lights, no fans, nothing.

### 2. Establish a Theory of Probable Cause

With a dead-on-arrival symptom like this, I work through the likely causes starting with the simplest:

- Not receiving power at all (bad outlet, unplugged cable, faulty cord)
- Power supply unit (PSU) failure
- Internal hardware failure (motherboard, component-level)
- User error (power switch not fully engaged, PSU switch flipped off)

Always cheapest and simplest first. No reason to crack the case open before ruling out the outlet.

### 3. Test the Theory

- Test the outlet with a known-working device to rule out the wall.
- Inspect the power cable and every connection point.
- Test the PSU directly with a PSU tester, or swap in a known-good unit.
- Open the case and reseat/verify all internal cable connections.

**Result:** The outlet and cable check out fine, but the computer still won't power on. That points toward the PSU or something downstream of it.

### 4. Establish a Plan of Action and Implement the Solution

Testing points to the PSU as the failure point. I swap it for a known-working unit, reconnect every cable I touched, and attempt to power the system back on.

### 5. Verify Full System Functionality and Implement Preventive Measures

Once it powers on, I don't just call it done. I check that it boots fully and that keyboard, mouse, and monitor are all responding correctly. On the preventive side, I recommend a surge protector or UPS and talk through proper shutdown habits, since abrupt power loss is a common way PSUs get stressed in the first place.

**Verification:** System powers on and boots normally. User confirms everything's working as expected.

### 6. Document Findings, Actions, and Outcomes

Closing out the ticket with a clear record:

- **Problem:** Computer wouldn't power on
- **Cause:** Faulty PSU
- **Action:** Replaced PSU, verified all connections, tested functionality
- **Outcome:** Computer fully operational
- **Notes:** Recommended surge protector/UPS and proper shutdown procedures going forward

## Skills I Picked Up

- Applying the six-step troubleshooting methodology in order instead of skipping to a guess.
- Isolating a hardware fault by testing from the outside in (outlet, then cable, then PSU, then internals).
- Writing up a ticket resolution in a way that's actually useful if someone else has to reference it later.

## How This Applies in the Real World

No-power tickets are one of the most common hardware calls an IT tech gets, and it's easy to waste time replacing the wrong part if you skip straight to a guess. Working the methodology in order, cheapest and simplest checks first, saves time, avoids unnecessary parts swaps, and gives a clean paper trail if the issue comes back.

## Limitations

This is a scenario write-up, not a hands-on repair. There's no physical PSU tester reading or photos of the internals to back it up. In a real ticket I'd also want the exact PSU model/wattage and to check for burn marks or bulging capacitors before assuming a clean swap fixes it.

## References

- [CompTIA A+ Troubleshooting Methodology](https://www.comptia.org/certifications/a)
- [How to Test a Power Supply (PSU)](https://www.pcmag.com/how-to/how-to-test-a-power-supply)
