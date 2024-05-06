# Multiplexer4to1
# Truth Table
![image](https://github.com/RESMIRNAIR/Multiplexer4to1/assets/154305926/f1dac9e1-e938-4072-bfa9-c17a0a54b7c7)
# Circuit Diagram
![image](https://github.com/RESMIRNAIR/Multiplexer4to1/assets/154305926/f8ea8610-f6fc-4de3-a68a-5a9a4cfcd673)
# PROGRAM:
module mux(a,b,d,y);

input a,b;

input [3:0]d;

output y;

wire w1,w2,w3,w4;

assign w1=~a&~b&d[0];

assign w2=~a&b&d[1];

assign w3=~a&~b&d[2];

assign w4=a&b&d[3];

assign y=w1|w2|w3|w4;

endmodule

# OUTPUT:
![image](https://github.com/SivaShankar33/Multiplexer4to1/assets/125188331/763b1418-3c48-4df7-ac72-107f7da432b9)
