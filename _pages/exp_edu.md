<style>
  table {
    margin-bottom: 1rem;
    width: 100%;
    font-size: 85%;
    border: 0px solid $border-color;
    border-collapse: collapse;
  }

  td,
  th {
    padding: 1rem .25rem;
    border: 0px solid $border-color;
  }

  th {
    text-align: left;
  }

  tbody tr:nth-child(odd) td,
  tbody tr:nth-child(odd) th {
    background-color: transparent;
  }

  paper {
    color: #;
    font-weight: bold;
  }
</style>

<table width="100%" align="center" border="0" cellspacing="0" cellpadding="20">
  <tr>
    <th>Work Experience</th>
  </tr>
  <tr>
    <td width="14%" valign="top">
      <img src="/images/work/bsc.png" alt="Barcelona Supercomputing Center" style="vertical-align:top; width: 80%; margin:0px 10px; border-radius:0%" />
    </td>
    <td valign="top" width="85%">
      <p>
        <paper>Research Engineer 3 (Senior Research Engineer) at Barcelona Supercomputing Center</paper><br>
        <em>Barcelona, Spain</em><br>
        September, 2023 - January 2024
        <details>
          <summary>Details</summary>
          <p class="message">
            <ul>
              <li>Worked on designing a software hardware (PS-PL) framework with Zynq ultra-scale MPSoC and accelerated algorithms for a microsatellite.</li>
              <li>Reviewed papers for the DATE conference 2024 on computer architecture and EDA tools. Gave appropriate feedback to improve on these papers.</li>
              <li>Worked on pipelining kernels of the algorithm with no data dependency with Dynamic function exchange and Partial dynamic reconfiguration features offered by the Zynq Ultrascale+.</li>
              <li>Resolved bugs on the kernel, rootfs, drivers, device tree, deployed and tested openmp, fpga manager and utils on petalinux builds.</li>
              <li>Setup the MPSoC available across VPN by setting it up on the existing networking infrastructure at BSC enabling remote deployment, orchestration, build over tftp and debugging (over ethernet and Serial connections).</li>
              <li>Xilinx UltraScale MPSOC, Vitis & Vivado Development, PetaLinux, SDSoC & SDAccel Xilinx development, device tree configuration, Arm Cortex A53, Arm cortex R5, Kernel & rootfs build.</li>
            </ul>
          </p>
        </details>
      </p>
    </td>
  </tr>

  </table>