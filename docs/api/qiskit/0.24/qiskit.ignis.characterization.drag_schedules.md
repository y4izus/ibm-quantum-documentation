<span id="qiskit-ignis-characterization-drag-schedules" />

# qiskit.ignis.characterization.drag\_schedules

<span id="undefined" />

`drag_schedules(beta_list, qubits, pulse_amp, pulse_width, pulse_sigma=None, width_sigma_ratio=4, drives=None, inst_map=None, meas_map=None)`

Generates schedules for a drag experiment doing a pulse then the - pulse

**Parameters**

*   **beta\_list** (*list of floats*) – List of relative amplitudes
*   **the derivative pulse** (*for*) –
*   **qubits** (*list of integers*) – indices of the qubits to perform a rabi
*   **pulse\_amp** (*list*) – amp of the gaussian (list of length qubits)
*   **pulse\_width** (*float*) – width of gaussian (in dt units)
*   **pulse\_sigma** (*float*) – sigma of gaussian
*   **width\_sigma\_ratio** (*int*) – set sigma to a certain ratio of the width (use if pulse\_sigma is None)
*   **drives** (*list*) – list of [`DriveChannel`](qiskit.pulse.DriveChannel#qiskit.pulse.DriveChannel "qiskit.pulse.DriveChannel") objects
*   **inst\_map** ([*InstructionScheduleMap*](qiskit.pulse.InstructionScheduleMap#qiskit.pulse.InstructionScheduleMap "qiskit.pulse.InstructionScheduleMap")) – InstructionScheduleMap object to use
*   **meas\_map** (*list*) – meas\_map to use

**Returns**

A list of QuantumSchedules xdata: a list of amps

**Raises**

**QiskitError** – when necessary variables are not supplied.