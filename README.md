# LTSpice-code
Version 4
SHEET 1 880 680
WIRE -16 16 -64 16
WIRE 144 16 48 16
WIRE -64 48 -64 16
WIRE 144 48 144 16
WIRE -64 160 -64 128
WIRE 48 160 -64 160
WIRE 144 160 144 128
WIRE 144 160 48 160
WIRE 48 192 48 160
FLAG 48 192 0
FLAG -64 16 n001
FLAG 144 16 n002
SYMBOL memristor 128 32 R0
SYMATTR InstName U1
SYMBOL cap -16 32 R270
WINDOW 0 32 32 VTop 2
WINDOW 3 0 32 VBottom 2
SYMATTR InstName C1
SYMATTR Value 100µ
SYMBOL voltage -64 32 R0
WINDOW 3 -78 103 Left 2
WINDOW 123 0 0 Left 0
WINDOW 39 0 0 Left 0
SYMATTR Value PULSE(0 1 0 0 0 .1 .2 7)
SYMATTR InstName V1
TEXT -80 176 Left 2 !.tran 1.4
