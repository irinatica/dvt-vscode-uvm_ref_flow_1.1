----------------------------------------------------------------------
Copyright 1999-2010 Cadence Design Systems, Inc.
All Rights Reserved Worldwide

Licensed under the Apache License, Version 2.0 (the
"License"); you may not use this file except in
compliance with the License.  You may obtain a copy of
the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in
writing, software distributed under the License is
distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR
CONDITIONS OF ANY KIND, either express or implied.  See
the License for the specific language governing
permissions and limitations under the License.
----------------------------------------------------------------------
* Title       : UART block level Test bench
* Name        : uart_ctrl
* Modified    : March 2011
* Version     : 1.02
* Comments to : uvm_ref@cadence.com

* Description:

This package contains UART block level testbench

The package contains the following directories:

    e/         :  Enviroment source files

    sve/       : Simulation verification environement  
        e/       : SVE for UVM compliant module UVC 
        scripts/ : Scripts for simulation purpose
        tests/   : module environment testcase.  

* Installation:

    Please refer the following file for Installation.

        $UVM_REF_HOME/README.txt

* Demo:

To run the demo: 
  
  Issue the following command in a suitable simulation directory:

    $UVM_REF_HOME/soc_verification_lib/uvm_e_ex_lib/uart_ctrl/demo.csh

To run a testcase : 

    $UVM_REF_HOME/soc_verification_lib/uvm_e_ex_lib/uart_ctrl/sve/scripts/run_sim.sh -test <testname> -run_mode <interactive_debug|batch> -seed <seed>

    - If seed value is not specified , random seed will be selected.
    - Default intelligen will be selected for all the sims.

Eg: $UVM_REF_HOME/soc_verification_lib/uvm_e_ex_lib/uart_ctrl/sve/scripts/run_sim.sh -test data_poll -run_mode batch -seed 1
