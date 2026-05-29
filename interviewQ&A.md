# Most Important LangGraph Interview Questions

## 1. What are the core components of LangGraph?

### Answer

Nodes, edges, and state.

---

## 2. Why is `Annotated` used with state?

### Answer

To attach reducers like `add_messages` for controlled state updates.

---

## 3. What does `add_messages` do?

### Answer

It appends new messages to existing state instead of overwriting them.

---

## 4. Why is StateGraph important?

### Answer

It enables stateful multi-step workflow execution.

---

## 5. What are conditional edges?

### Answer

Edges that dynamically decide the next node based on runtime conditions.

---

## 6. Why are ReAct agents better than simple StateGraphs for multiple tool calls?

### Answer

Because ReAct agents iteratively reason after every tool execution and dynamically decide the next action.

---

## 7. Difference between Graph API and Functional API?

### Answer

Graph API provides explicit workflow control, while Functional API offers simpler function-based workflow definitions.

---

## 8. Why use reducers in LangGraph?

### Answer

Reducers control how multiple state updates merge without overwriting data.

---

## 9. What is the purpose of streaming in LangGraph?

### Answer

Streaming provides incremental outputs in real-time during graph execution.

---

## 10. What is shared state in LangGraph?

### Answer

Shared state is the central memory passed between nodes during execution.

---

# Best Interview One-Liner

> "LangGraph enables stateful, controllable, and dynamic AI workflows using nodes, edges, reducers, and shared state management."

# Most Important Interview Questions

## 1. What is ReAct architecture?

### Answer

ReAct combines reasoning, action, and observation loops to enable intelligent multi-step agent behavior.

---

## 2. Why are ReAct agents better than simple workflows?

### Answer

Because they iteratively reason after each tool execution and dynamically plan future actions.

---

## 3. What is checkpointing in LangGraph?

### Answer

Checkpointing persistently stores workflow state for recovery and continuation.

---

## 4. Why is `thread_id` important?

### Answer

It uniquely identifies conversation sessions and enables persistent memory retrieval.

---

## 5. Difference between `.stream()` and `.astream()`?

### Answer

`.stream()` is synchronous while `.astream()` is asynchronous and supports non-blocking concurrent execution.

---

## 6. Difference between `values` and `updates` stream mode?

### Answer

`values` streams full graph state, while `updates` streams only incremental changes.

---

## 7. Why does `astream_events()` provide more detailed output?

### Answer

Because it streams internal execution events such as node execution, state updates, and tool calls.

---

## 8. What is Interrupt in HITL?

### Answer

Interrupt pauses execution and waits for human or external input before continuing.

---

## 9. What is Command in LangGraph?

### Answer

Command controls workflow continuation after interruption or decision points.

---

## 10. Why is async execution important in AI agents?

### Answer

Async improves scalability, concurrency, responsiveness, and efficient execution of multiple tasks.

---

# Best Interview One-Liner

> "LangGraph combines stateful workflows, streaming, checkpointing, and human-in-the-loop capabilities to build scalable and production-grade AI agent systems."