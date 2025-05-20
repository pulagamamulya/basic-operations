module gate(
    input [7:0] a, b,
    output [7:0] sum, diff, and_out, or_out, not_a
);
    assign sum = a + b;
    assign diff = a - b;
    assign and_out = a & b;
    assign or_out = a | b;
    assign not_a = ~a;
endmodule
