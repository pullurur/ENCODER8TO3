# ENCODER8TO3

AIM:

To simulate and synthesis Encoder using vivado.

APPARATUS REQUIRED:

vivado 2023.2 software.

PROCEDURE:

STEP:1 Start the vivado software, Select and Name the New project.

STEP:2 Select the device family, device, package and speed.

STEP:3 Select new source in the New Project and select Verilog Module as the Source type.

STEP:4 Type the File Name and module name and Click Next and then finish button. Type the code and save it.

STEP:5 Select the run simulation and then run Behavioral Simulation in the Source Window and click the check syntax.

STEP:6 Click the simulation to simulate the program and give the inputs and verify the outputs as per the truth table.

STEP:7 compare the output with truth table.

AIM:

To simulate and synthesis Encoder using vivado.

APPARATUS REQUIRED:

vivado 2023.2 software.

PROCEDURE:

STEP:1 Start the vivado software, Select and Name the New project.

STEP:2 Select the device family, device, package and speed.

STEP:3 Select new source in the New Project and select Verilog Module as the Source type.

STEP:4 Type the File Name and module name and Click Next and then finish button. Type the code and save it.

STEP:5 Select the run simulation and then run Behavioral Simulation in the Source Window and click the check syntax.

STEP:6 Click the simulation to simulate the program and give the inputs and verify the outputs as per the truth table.

STEP:7 compare the output with truth table.

![301809043-824226c8-c767-44b5-ab35-26fed65b195e](https://github.com/pullurur/ENCODER8TO3/assets/161436550/9b5f641a-ceae-4ff2-9138-904933cc9bc2)

Truth Table

![301809102-e228c14b-b814-40c8-92eb-748d48570c04](https://github.com/pullurur/ENCODER8TO3/assets/161436550/085ecf63-bf18-435e-865c-461d6af4f780)


Circuit Diagram

![301809216-6fa5fe84-fe6f-472d-b9c0-e6dfa17413d3](https://github.com/pullurur/ENCODER8TO3/assets/161436550/7e0edad9-cf26-4f64-86a5-c95ba8fd5b3e)

![301809295-7d147e2a-ba03-4714-baee-17615c9c50c1](https://github.com/pullurur/ENCODER8TO3/assets/161436550/215eedde-17bc-4f86-bcc2-bed674afe2a2)



VERILOG CODE:

module encoder(d,a,b,c);

input [7:0]d;

output a,b,c;

or (a,d[4],d[5],d[6],d[7]);

or (b,d[2],d[3],d[6],d[7]);

or (c,d[1],d[3],d[5],d[7]);

endmodule

OUTPUT:

![318266960-f9160684-7565-4781-954e-77429e0a8232](https://github.com/pullurur/ENCODER8TO3/assets/161436550/4109925b-a5c6-4fa2-b01a-381906e6aa51)


RESULT:

Thus, the verilog program for Encoder has been simulated and verified successfully.

