# OBJECTIVE OF THIS PROJECT
 * In many cases, the majority of street lights, outdoor lighting, and a variety of indoor house equipment are manually operated and maintained. This is not only dangerous, but it also wastes energy due to employee negligence or unusual situations when turning on and off these electrical appliances.The resistance changes when light shines on the resistor. These resistors are commonly employed in many circuits that need the detection of light. These resistors come in a range of shapes and sizes, as well as resistance levels.


# INTODUCTION
 * The LDRs are used in a bridge sensor circuit to convert light into voltage, allowing various actions to be performed, such as determining the darkness in the room and turning on or off the light by feeding the voltage signal into the microcontroller.The conductivity of a substance improves when light is absorbed by it. The electrons in the valence band of the material rush to the conduction band when light shines on the LDR.


# PRINCIPLE
 * These devices are light-dependent; when light falls on the LDR, the resistance decreases, while in the dark, it increases. When an LDR is kept in the dark, it has a high resistance, and when it is maintained in the light, it has a lower resistance.When light is absorbed by the substance, the material's conductivity improves. When light shines on the LDR, the electrons in the material's valence band rush to the conduction band.

# COMPONENTS AND SUPPLIES
 * Atmega 328
 * 3 LEDs
 * voltage source
 * LDR
 * 4 Resistors
 * Audio out

# ADVANTAGES 
 * The wavelength of the incoming light and the semiconductor material determine the sensitivity.
 * The frequency response (the device's capacity to detect rapidly changing optical signals) is quite low.
 * Under bright illumination, photoelectric conversion linearity is weak.

# DISADVANTAGES
 * The frequency response of the ldr light dependent resistor (its capacity to detect rapidly changing optical signals) is quite low.
 * Temperature has a significant impact on it, and it has a slow response time.
 * The illumination of the incident light (photodiode has no flaws, and photodiode sensitivity is higher than LDR sensor), which is a consumable material, affects the delay time between MS and S.

# LIMITATIONS
 * To properly respond to changes in light intensity, they need a few milliseconds or more.
 * Once light is removed, they will need a few seconds to return to their typical dark resistance. 
 * The LDRs' sensitivity and resistance range will differ from one device to the next.

# HIGH LEVEL REQUIREMENTS
| ID | Description | Status |
| ---|:------------|:-------|
| HL01 | LDR INTERFACING WITH ATMEGA328 | IMPLEMENTED |
| HL02 | BUZZER INTERFACING | IMPLEMENTED |

# LOW LEVEL REQUIREMENTS
| ID | Description | Status |
| ---|:------------|:-------|
| HL01-LL01 | ABLE TO DETECT THE INTENSITY OF LEDs WITH LDR | IMPLEMENTED |
| HL01-LL02 | LDR INTERFACING WITH ATMEGA328 | IMPLEMENTED |
| HL02-LL02 | BUZZER INDICATES THE INTENSITY OF LEDs	| IMPLEMENTED

# 4W and H

## WHO
* LDR Sensor is using in most of the organization.

## WHAT
* These devices are light-dependent; when light shines on the LDR, the resistance drops, whereas in the dark, it increases. When an LDR is kept in the dark, it has a high resistance, and when it is maintained in the light, it has a lower resistance.

## WHERE
* These devices are employed in situations where it is important to detect the presence and absence of light. These resistors are employed as light sensors in alarm clocks, street lights, light intensity metres, and burglar alarm circuits, among other things.

## WHEN
* Light dependent resistors (LDR) are light-sensitive devices that are commonly used to detect the presence or absence of light, as well as to measure the intensity of light.

## HOW
* Their resistance lowers as the light intensity increases: an LDR's resistance is high in the dark and at low light levels, and only a small amount of current may flow through it.








