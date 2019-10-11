## 1: CLOCKS AND RESET

Registers: FF04

Clock division and distribution. Reset signal buffering and distribution.

## 2: INTERRUPTS

Registers: FF0F

Joypad interrupt generation. Interrupt registering and acknowledgement.

## 3: TIMER

Registers: FF05, FF06, FF07

Clock selection, timer counter and comparator. Timer interrupt generation.

## 4: DMA

Registers: FF46

Address counter, access sequencer.

## 5: JOYPAD I/O

Registers: FF00

External I/O, special handling for test modes.

## 6: SERIAL LINK

Registers: FF01, FF02

Bit counter, shift register, serial interrupt generation.

## 7: SYS DECODE

Registers: FF50, FF60

Boot ROM address decoding, lockout, HRAM decoding, test register.

## 8: EXT CPU BUSSES

Address and data bus direction control, multiplexing and buffering.

## 9: APU CONTROL

Registers: FF24, FF25, FF26

Audio section clock generation, reset distribution.

## 10: APU DECODE

Decoding for all the audio-related registers. Analog section power control.

## 11: CH1 REGS

Registers: FF10, FF11, FF12, FF13, FF14

Sound channel 1 registers read/write.

## 12: CH1 SWEEP

Registers: FF13, FF14

Sound channel 1 frequency sweep logic.

## 13: CHANNEL 1

Sound channel 1 main logic: Length timer, EG timer, EG, sweep timer, sweep shift counter, waveform duty selection.

## 14: CH2 REGS

Registers: FF16, FF17, FF18, FF19

Sound channel 2 registers read/write.

## 15: CHANNEL 2

Sound channel 2 main logic: Length timer, EG timer, EG, waveform duty selection.

## 16: CH3 REGS

Registers: FF1A, FF1B, FF1C, FF1D, FF1E

Sound channel 3 registers read/write.

## 17: WAVE RAM

CPU and APU read access control for Wave RAM, byte splitter.

## 18: CHANNEL 3

Sound channel 3 main logic: Length timer, attenuator, wave RAM address generator.

## 19: CH4 REGS

Registers: FF20, FF21, FF22, FF23

Sound channel 4 registers read/write.

## 20: CHANNEL 4

Sound channel 4 main logic: Length timer, EG timer, EG, frequency selection, LFSR.

## 21: VIDEO CONTROL

Registers: FF41

Video sequencing, interrupt generation, X and Y counters, raster number comparator.

## 22: PPU DECODE

Decoding for all the video-related registers.

## 23: VIDEO REGS

Registers: FF40, FF42, FF43, FF44, FF45, FF4A, FF4B

Video registers read/write.

## 24: LCD CONTROL

Signal generation for the LCD. Horizontal and vertical sync along with others.

## 25: VRAM INTERFACE

Address and data bus direction control, multiplexing, buffering and control signal generation for external VRAM.

## 26: BACKGROUND

Background layer tile map address generation, shifter for the BG-to-sprite priority bit.

## 27: WINDOW MAP LOOKUP

Window layer tile map address generation, window and background rendering logic, X and Y comparators.

## 28: OAM

Sequencing and arbitrating, parsing counter, address multiplexing, control signal generation.

## 29: SPRITE CONTROL

Raster comparator for sprite parsing, X priority, more sequencing logic, triggers for sprite store.

## 30: SPRITE STORE

Ten 10-bit registers storing Y-matched sprite numbers (6 bits) and rendering raster indexes (4 bits).

## 31: SPRITE X MATCHERS

Ten X comparators used to detect when to start rendering sprites.

## 32: BG PIXEL SHIFTER

Background pixel data loader and shifters.

## 33: SPRITE PIXEL SHIFTER

Sprite pixel data loader and shifters.

## 34: SPRITE PALETTE SHIFTER

Sprite palette loader and shifter, pixel opacity detection.

## 35: PIXEL MUX

Pixel data multiplexing between background, sprite palette 0 and sprite palette 1 for final output.

## 36: PALETTES

Registers: FF47, FF48, FF49

Palette registers read/write.
