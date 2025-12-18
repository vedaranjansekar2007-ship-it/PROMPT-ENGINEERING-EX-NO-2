# EX-02-Cross-Platform-Prompting-Evaluating-Diverse-Techniques-in-AI-Powered-Text-Summarization

## AIM
To evaluate and compare the effectiveness of prompting techniques (zero-shot, few-shot, chain-of-thought, role-based) across different AI platforms (e.g., ChatGPT, Gemini, Claude, Copilot) in a specific task: text summarization.

## ALGORITHM:
1. Start the experiment
2. Give a Zero-shot prompt, Few-shot prompt, Role-Based prompt and Chain-of-thought prompt to a different AI tools such as ChatGPT, Claude, Microsoft Copilot, Gemini.
3. Analyzing the outputs given the tools.
4. Conclude the experiment. 

## OUTPUT:
Scenario 1: Zero-shot Prompting <br> 
prompt 1: Explain gravity in one simple line <br> 
     Ans: Gravity is the force that pulls objects toward each other, especially toward the Earth. (ChatGPT) <br>
     Ans: Gravity is the invisible force of attraction that pulls all objects with mass toward one another. (Gemini) <br>
     Ans: Gravity is the force that pulls objects with mass toward each other, which is why things fall to the ground and planets orbit stars. (Claude) <br> 
     Ans: Gravity is the invisible force that pulls objects toward each other, keeping planets, stars, and us grounded. (Copilot) <br>

Scenario 2: Few-shot Prompting <br> 
prompt 2: Example: Car – used for travel <br> 
          Example: Phone – used for communication <br>
          Task: Laptop – used for what? <br> 
     Ans: Laptop – used for computing and work tasks such as studying, coding, and creating documents. (ChatGPT) <br>
     Ans: Laptop – used for productivity and information. (Gemini) <br>
     Ans: Laptop – used for computing and work. (Claude) <br>
     Ans: Laptop – used for work, study, and entertainment. (Copilot) <br> 

Scenario 3: Chain-of-thought prompting <br>
prompt 3: Explain step-by-step to find the LCM of 12 and 18 <br>
     Ans: 1.Write the prime factors of each number <br>
          * 12 = 2 × 2 × 3 = 2² × 3 <br>
          * 18 = 2 × 3 × 3 = 2 × 3² <br>
          2. Take the highest power of each prime factor <br> 
          * Highest power of 2 → 2² <br>
          * Highest power of 3 → 3² <br>
          3. Multiply them together <br>
          * LCM = 2² × 3² = 4 × 9 = 36 <br> 
          LCM of 12 and 18 is 36 (ChatGPT) <br>
     Ans: To find the LCM (Least Common Multiple) of 12 and 18 concisely, use the Listing Multiples method: <br>
          List multiples of 12: 12, 24, 36, 48 <br>
          List multiples of 18: 18, 36, 54 <br>
          Identify the smallest match: The first number to appear in both lists is 36. <br>
          LCM = 36 (Gemini) <br> 
     Ans: Step 1: Find the prime factorization of each number. <br>
          12 = 2 × 2 × 3 = 2² × 3 <br>
          18 = 2 × 3 × 3 = 2 × 3² <br> 
          Step 2: Identify all prime factors that appear in either number. <br> 
          The prime factors are: 2 and 3 <br> 
          Step 3: For each prime factor, take the highest power that appears in either factorization. <br>
          Highest power of 2: 2² (from 12) <br>
          Highest power of 3: 3² (from 18) <br> 
          Step 4: Multiply these highest powers together. <br> 
          LCM = 2² × 3² = 4 × 9 = 36 <br> 
          Answer: The LCM of 12 and 18 is 36. (Claude) <br>
     Ans: Multiples of 12: 12, 24, 36, 48 <br>
          Multiples of 18: 18, 36, 54 <br> 
          First common multiple: 36 <br>
          Answer: The LCM of 12 and 18 is 36. (Copilot) <br><br>
Scenario 4: Role-Based Prompting <br>
prompt 4: I'm 10th standard school boy. Explain Quantum optics <br>
     Ans: Quantum optics is the study of light at a very small (atomic) level. <br>
          It explains that light is made of tiny energy packets called photons and can behave as both a wave and a particle. <br>
          This concept helps us understand technologies like lasers, optical fibers, and quantum communication. (ChatGPT) <br>
     Ans: 1. Light as "Packets" <br> 
          In quantum optics, we don't just see light as a continuous beam. We treat it as being made of tiny, individual packets of energy called photons. <br>
          2. The Core Idea <br> 
          It explores how these photons interact with atoms and subatomic particles. Think of it this way: <br> 
          Classical Optics: Light is like a flowing river of water. <br>
          Quantum Optics: Light is like a stream of individual water droplets. <br>
          3. Key Concepts to Know <br> 
          Quantization: Energy isn't continuous; it comes in specific "chunks." <br>
          Wave-Particle Duality: Light has a "split personality"—it acts as both a wave and a particle depending on how you measure it. <br> 
          Photon Interference: Individual photons can interfere with themselves, leading to strange results that classical physics can't explain. <br> 
          4. Real-World Uses <br>
          You already use the results of quantum optics every day! <br>
          Lasers: Precise beams of light used in surgery and barcode scanners. <br>
          Fiber Optics: High-speed internet sent via light pulses. <br> 
          Quantum Computers: The future of super-fast computing. (Gemini) <br>
     Ans: What is Quantum Optics? <br>
          Quantum optics is the study of light at the smallest possible level - understanding light as tiny packets of energy called photons rather than just waves. <br>
          Key Idea: <br>
          You've learned that light behaves as a wave (like ripples in water). But quantum optics shows that light also behaves as particles (photons) - like tiny balls of energy. This is<br>              called wave-particle duality. <br>
          Simple Example: <br>
          Think of a dim light bulb. Classical physics says light flows continuously like water from a tap. But quantum optics reveals that the light is actually made of billions of <br>                     individual photons shooting out one by one - so fast you can't see the gaps! (Claude) <br>
     Ans: Quantum optics is the study of light at the quantum level, where light is treated as tiny particles called photons and we explore how they interact with matter. <br>
          Quick Teacher-Style Breakdown 👨‍🏫 <br> 
          Light as photons: Instead of just waves, light is made of energy packets called photons. <br> 
          Photon–matter interaction: Quantum optics looks at how these photons interact with atoms and molecules. <br>
          Applications: Used in lasers, quantum computers, secure communication, and even experiments on entanglement and teleportation. <br>
          Key idea: It connects quantum mechanics with optics, showing how the smallest units of light behave in surprising ways. <br> 
## RESULT:
Above are the outputs which is given AI tools according to the following prompts such as zero-shot, few-shot, chain-of-thought and role-based.
