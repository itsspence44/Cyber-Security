# Review of class 

# What Makes an AI System Trustworthy?

*Characteristics, evidence, and the difference between trust and reliability* 

**Trustworthiness Is Not the Same as Accuracy** 

An AI system can be accurate on average while being systematically wrong for specific groups or contexts

An AI system can perform well in testing and fail in deployment due to distribution shift

An AI system can be technically correct but opaque — making it unverifiable and therefore untrustworthy


**The NIST AI Risk Management Framework (AI RMF) identifies characteristics of trustworthy AI:** 

Accuracy — produces correct outputs for the intended task

Reliability — performs consistently across conditions and over time

Explainability — outputs and reasoning can be understood by relevant stakeholders

Fairness — does not produce unjustified disparate outcomes for different groups

Privacy — protects personal information used in training or inference

Security — is robust against adversarial manipulation and data poisoning

Accountability — there are clear human roles responsible for oversight and correction



**Applying Trustworthiness Characteristics to the SOC Platform**

**Accuracy** 

The platform produced three correct detections and multiple incorrect actions.
What is the overall precision and recall? Are errors randomly distributed, or
concentrated in specific populations or contexts?



**Security** 

Could an attacker manipulate the platform's detection by mimicking legitimate
behavioral patterns? Has the platform been tested for adversarial evasion? AI -
enabled defenses can be gamed



**Explainability** 

When the platform flagged the senior engineer's account, could it explain why?
When it blocked red team tools, what evidence did it cite? Operators must be
able to evaluate the platform's reasoning.


# Bias — Sources, Types & System-Wide Thinking

*Bias can enter an AI system in many ways — not only through training data* 

**Why "Biased Training Data" Is Not the Whole Story** 

The most common explanation for AI bias is biased training data — this is real, but incomplete

Bias can enter an AI-enabled system at every stage of its design, development, and deployment

Identifying and addressing harmful bias requires examining the entire system



**Twelve Sources of Bias in AI-Enabled Systems** 


**Historical Data**

Training on past decisions that reflected historical discrimination encodes those
patterns into the model. Past does not equal correct.

**Labels and Measurement**

Human annotators make judgment calls. If annotators share assumptions, those
assumptions become labels. The thing being measured may not be the thing
that matters



**Proxy Variables**

A model may use a variable that correlates with a protected characteristic — ZIP
code for race, job title for gender. The model never "sees" the protected class,
but the effect is the same

**Thresholds and Deployment** 

A threshold that produces equal false-positive rates in testing may have
unequal real-world impact if the populations it affects have different underlying
base rates





# The NIST AI Risk Management Framework



The NIST AI RMF (published January 2023) provides a voluntary framework for managing AI risk

It organizes AI risk management around four core functions:

GOVERN — establishing organizational policies, roles, and accountability structures

MAP — identifying AI risks in context — stakeholders, use cases, potential harms

MEASURE — quantifying and evaluating risks using appropriate metrics and method








**links** 
