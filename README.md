• Designed and implemented a fully synthesizable FPGA-based CNN accelerator in Verilog for 8-bit quantized
inference, supporting convolution, activation, normalization, and max-pooling operations.
• Architected a sliding-window convolution engine using line buffers and window-generation logic to efficiently
reuse input feature-map data, reducing redundant memory accesses during 3×3 convolutions.
• Developed a parallel MAC-based processing architecture with FSM-controlled scheduling, multi-channel
convolution support, and pipelined layer execution for efficient FPGA deployment — RTL simulation confirming
projected latencies of 0.25 ms (MNIST) and 15.93 ms (CIFAR-10) at 128-PE configuration.
