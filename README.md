使用iverilog编译：
iverilog -o test tb_axi_stream_insert_header.v axi_stream_insert_header.v

输出波形文件：
vvp -n test -lxt2

使用gtkwave读取波形：
gtkwave test.vcd
