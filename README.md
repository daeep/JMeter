# JMeter Test Plans and Component Examples

This repository contains a comprehensive collection of **Apache JMeter** test plans, reusable components, and function examples. It is designed to help you quickly build, customize, and understand JMeter test plans for various protocols and scenarios.

---

## Repository Structure

### JMeter_Examples

Contains example test plans and reusable components organized by category:

- **Component Examples**
  - **Assertions**: Examples of different assertion types (Response, JSON, XML, MD5, Size, Duration, HTML, JSR223, Compare).
  - **Config Elements**: Examples of CSV Data Set, HTTP Cache Manager, HTTP Cookie Manager, HTTP Header Manager, HTTP Request Defaults.
  - **Controllers**: Example Thread Group.
  - **Timers**: Constant Timer, Constant Throughput Timer, Gaussian Random Timer, Poisson Random Timer, Precise Throughput Timer, Synchronizing Timer, Uniform Random Timer.

- **FTP**
  - `FTP_Test.jmx`: *FTP Test Plan* demonstrating FTP request configuration with DNS caching.

- **HTTP**
  - **MicroServices**
    - `Dummy_Json.jmx`: *Dummy REST JSON Test Plan* for simple REST API testing.
    - `REST_API_Json.jmx`: *Microservices REST API Test Plan* template for API endpoint testing.
  - **Recording**
    - `Recording.jmx` and `Recording_Timer.jmx`: Templates for recording HTTP requests.
  - **Web**
    - `Flood_Challenge.jmx`, `Webtours_-_Workload_If_Controller.jmx`, `Webtours_-_Workload_Throughput_Controller.jmx`: Web application workload simulations.

- **Misc**
  - `Random.jmx`: Miscellaneous test elements.

- **SMTP**
  - `SMTP_Test.jmx`: Example SMTP email test plan.

- **Websocket**
  - `WebSocket-Maciej.jmx`, `WebSocket-Peter.jmx`: WebSocket protocol test examples.

---

### JMeter_Functions

Reusable function examples grouped by category:

- `Calculation-functions.jmx`
- `Information-functions.jmx`
- `Properties-functions.jmx`
- `Scripting-functions.jmx`
- `Strings-functions.jmx`
- `Variables-functions.jmx`

These files demonstrate how to use JMeter built-in functions and scripting capabilities.

---

### The_Internet_Herokuapp+New_Relic

- `NewRelic.jmx`: Example integration or monitoring test plan.

---

## How to Use

1. **Open JMeter GUI** (version 5.0 or compatible).
2. **Import any `.jmx` file** via `File` > `Open`.
3. **Customize the test plan** as needed:
   - Set thread counts, loops, and variables.
   - Modify endpoints, payloads, and assertions.
4. **Run the test** and analyze results using JMeter listeners.

---

## Purpose

This repository serves as a **reference library** for:
- Learning JMeter components and functions.
- Quickly assembling new test plans.
- Demonstrating protocol-specific testing (HTTP, FTP, SMTP, WebSocket).
- Providing templates for REST API and microservices testing.

---

## License

This repository is provided for educational and demonstration purposes.
