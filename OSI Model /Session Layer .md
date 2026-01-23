# 🔗 Session Layer (OSI Model – Layer 5)

The Session Layer is **Layer 5** of the OSI model.
It receives data from the **Presentation Layer** and is responsible for **establishing, managing, and terminating communication sessions** between two systems or applications.

---

A **session** is a logical connection that allows two applications to communicate continuously for a period of time.

---

## 🧠 Why the Session Layer is Needed

Without the Session Layer:

* Every request would be treated as a new connection
* Users would need to log in repeatedly
* Systems would not remember the communication state

The Session Layer ensures **continuity and organization of communication**.

---

## 🔑 Main Functions of the Session Layer

### 1️⃣ Session Establishment

* Creates a session between sender and receiver
* Example: user login, chat session, file transfer session

Once established, both sides recognize that a **session is active**.

---

### 2️⃣ Session Management (Session Control)

* Maintains the session while communication is ongoing
* Keeps track of the session state

Controls **dialog flow**:

* **Half-duplex**: one side sends at a time
* **Full-duplex**: both sides send simultaneously

---

### 3️⃣ Session Termination

* Properly closes the session when communication ends
* Example: logout, application close, session timeout

After termination, the session becomes **invalid**.

---

## 🔐 Authentication (Who are you?)

Authentication verifies the **identity of the user**.

### How it works:

* User provides credentials (username/password, OTP, etc.)
* Server verifies the credentials
* If valid, a session is created
* A session ID or token is assigned

After authentication:

* The user does not need to log in for every request
* The session proves the user’s identity

---

## 🛂 Authorization (What can you do?)

Authorization determines what an **authenticated user** is allowed to access.

### How it works:

* User is already authenticated
* System checks permissions linked to the session
* Access is allowed or denied based on roles

### Example:

* **Admin** → full access
* **User** → limited access

---

## 🔄 Session Recovery (Checkpoint Concept)

* Session Layer can maintain **checkpoints**

If communication is interrupted:

* Session can resume from the **last checkpoint**

> Actual retransmission of lost data is handled by the **Transport Layer**.

Session Layer manages **session continuity**, not packet reliability.

---

## 💻 How Data Reaches the User (Simplified Flow)

* User logs in → authenticated
* Session is created → session ID assigned
* Each request carries the session ID
* Server validates:

  * Session validity
  * Authorization
* Data is sent back to the user
* Session remains active until terminated

---

## 🚫 What the Session Layer Does NOT Do

* Does not encrypt data
* Does not route data
* Does not ensure reliable delivery

Those are handled by **other OSI layers**.

---

## ✅ Summary

* Manages logical communication sessions
* Maintains user login state
* Supports authentication and authorization context
* Controls dialog flow
* Handles session start, continuation, and end

---

## 📝 One-Line Definition

**The Session Layer establishes, manages, and terminates logical communication sessions between applications.**
