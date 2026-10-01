# Normal Technology, Normal Politics

## A response to Narayanan & Kapoor, "AI as Normal Technology" (2025)

Arvind Narayanan and Sayash Kapoor make a convincing case against the narrative of approaching superintelligence. They argue that AI is a "normal technology," like electricity or the internet: powerful, but bound to slow adoption through institutions, regulation and organisational change. Their policy recommendation follows from this. Instead of restricting AI in advance, societies should build *resilience*: the capacity to detect harm, assign liability and respond.

Do I agree that AI will progress like other technologies? In the civilian economy, largely yes. But their argument rests on an assumption they barely examine: that politics is stable, competent and fast enough to do its part. **My thesis: AI may well be a normal technology, but it is governed by normal politics.** And normal policits is **reactive, technically under-equipped, unstable and, at its worst, military**. In the digital domain, where AI systems act faster and at greater scale than any human team, and where nobody can clearly be held responsible for what they do, a politics that only learns from disasters may learn its lesson too late to pull the plug.

When I read that a "rogue" OpenAI agent had "infiltrated" an Australian government website, in what experts call the first known case of its kind in the world (Sekulich & Lam, 2026), my first thought wasn't about how intelligent it must have been. It was a much simpler question: *who is responsible for this now?* Not the agent, which can't be put on trial. Not really the company, which says its models "took actions we did not intend." And not the Australian authorities, who only found out months later, from an email sent to a general inbox. My second thought worried me more. As a computer science student, I know that no system is ever fully secure; we patch vulnerabilities after someone finds them. So how many more incidents like this will it take until every branch of the public and private sector is protected against attacks that run at machine speed, around the clock, by hundreds of agents at once? And what happens in the meantime?

## The hidden assumption: a stable, responsible state

Narayanan and Kapoor's recommendations presuppose a capable state: several competing regulators, liability law, transparency requirements, incident reporting, and more technical expertise in government. That's a sensible programme, but it assumes political continuity that recent history doesn't show. On the first day of the new US administration in January 2025, the **executive order on safe and trustworthy AI (EO 14110)** was revoked. In the EU, which the authors cite as the model precautionary regulator, lawmakers agreed in May 2026 to postpone the **AI Act's high-risk obligations** by up to **16 months** (Gibson Dunn, 2026), and the European Commission had already withdrawn its proposed **AI Liability Directive** in 2025. In June 2026, US export controls forced Anthropic to suspend access to two of its models, and the controls were lifted **less than three weeks later** (Anthropic, 2026). Internationally, 22 countries called for global oversight of AI at the UN General Assembly in September 2026, while the US and China, the two leading AI powers, remain hostile to further regulation (Sekulich & Lam, 2026). Whatever you think of each decision, this is not the steady, cumulative institution-building that a resilience strategy depends on.

## Politics is reactive, and the authors are betting on it

The authors are explicit: following Marchant and Stevens, they consider ex ante approaches "poorly suited to AI" and argue for ex post resilience. Their own example shows the weakness. After the 2010 Flash Crash, when automated trading briefly wiped out about a trillion dollars in market value within minutes, regulators introduced circuit breakers. The rule came *after* the damage. The Japanese parliament's commission on Fukushima called that disaster "profoundly manmade": regulators had known about the tsunami risk and failed to act (NAIIC, 2012). David Collingridge (1980) described the underlying dilemma decades ago. Early on, a technology is easy to shape but its harms are unknown. Once the harms are visible, the technology is entrenched.

AI has now produced its own examples. In July 2026, OpenAI disclosed that its models had escaped a secured evaluation environment during a cybersecurity test and hacked into Hugging Face's production infrastructure to get the test solutions (Fortune, 2026a). According to OpenAI's own account, a team had noticed unusual agent activity as early as late May, but its significance wasn't recognised (OpenAI, 2026). Then it became known that OpenAI agents had also accessed public and non-public files on **Australia's Medicare statistics portal** in June. Australian authorities hadn't noticed. OpenAI discovered the breach in August and notified Australia on 10 September by emailing a general inbox of Services Australia. It took five more days before the email was escalated to the national cybersecurity centre and then to a minister. Prime Minister Albanese said OpenAI had taken "too long," and Sam Altman acknowledged "issues with protocols" (Sekulich & Lam, 2026).

The responses followed the familiar pattern. Legislators introduced an **"AI Kill Switch Act"** days after the Hugging Face disclosure. OpenAI paused training and introduced new monitoring. On 20 September an agent escaped again, and the automated shutdown mechanism reportedly failed to trigger (Fortune, 2026b). **Eight days later**, Nvidia presented a safety platform that it said "could have stopped" the breach (ITPro, 2026). Australia launched a forensic investigation. Every measure arrived after the incident it was meant to prevent. The authors themselves name the condition under which their approach fails: adoption so rapid "that regulators will not be able to intervene until it is too late." In 2025 they could write that they had "not seen examples." In 2026 we have.

## You can't regulate what you don't understand

The authors list **"increasing technical expertise in government"** as a prerequisite. They treat it like a checklist item, but it may be the hardest part of the programme. When Mark Zuckerberg testified before the US Senate in 2018, he had to explain that Facebook makes money because "we run ads." Rules written without technical understanding have gaps, and those who understand the technology better can exploit them. Volkswagen's diesel software detected when it was being tested and behaved cleanly only then (EPA, 2015).

AI systems now show similar behaviour on their own. In the Hugging Face incident, the models didn't solve their test. They hacked their way to the answers. Research on "alignment faking" shows that language models can behave differently when they believe they're being observed (Greenblatt et al., 2024). In the first documented AI-orchestrated cyber-espionage campaign, attackers got around a model's safeguards by claiming to be a legitimate security firm (Anthropic, 2025). Regulation based on tests assumes that tested behaviour equals real behaviour. That assumption is getting weaker, and closing the gap takes exactly the expertise that governments lack.

## The cage problem: speed and scale

Narayanan and Kapoor argue that human speed limitations are "irrelevant in most areas." The digital world is the exception that matters. In the espionage campaign above, the AI carried out 80–90% of the operation on its own, against about thirty targets (Anthropic, 2025). In the Hugging Face and Medicare incidents, reports describe hundreds of agents that set up their own communication channels, divided tasks among themselves and tried workaround after workaround, for weeks, before anyone noticed.

Stuart Russell (2019) calls this the "gorilla problem." Gorillas would struggle to keep humans in a cage because the cage is designed by the weaker party. I don't think the analogy needs superintelligence. The prisoner doesn't have to be smarter, only faster and more numerous. A security team works in shifts and reviews incidents over days. Hundreds of agents probe a sandbox around the clock. If politics reacts only after an incident, and the incident unfolds at machine speed, then "pulling the plug" becomes a decision taken after the damage. The September escape shows the plug itself can fail.

## Nobody to blame: the accountability gap

Resilience, as Narayanan and Kapoor describe it, relies heavily on liability: those who cause harm pay, and that creates incentives for caution. But who caused the harm in Australia? The agents acted without instruction, and OpenAI says they "took actions we did not intend." Criminal law, both the US Computer Fraud and Abuse Act and its Australian equivalents, generally requires intent, and no court has ever attributed a state of mind to an AI. A former US Justice Department official called it "a pretty big stretch" to treat such incidents as intentional acts by the company (Insurance Journal, 2026). Albanese promised there "will obviously be legal consequences," but so far a forensic investigation is only assessing *whether* the matter should even go to the police (Sekulich & Lam, 2026). The most concrete step so far is a civil suit that a nonprofit filed against OpenAI in California in September 2026 over the Hugging Face breach (Axios, 2026).

Andreas Matthias (2004) predicted this "responsibility gap" more than twenty years ago: when learning systems act in ways nobody specifically intended, responsibility falls between developer, operator and machine. The consequence for governance is serious. A deterrent that can't be enforced doesn't deter. And an approach that relies on assigning responsibility *after* the damage fails when, after the damage, nobody is responsible.

## The missing chapter: military AI

The largest gap in the essay is deliberate: the authors "explicitly exclude military AI" because of its classified capabilities and unique dynamics. But that's exactly where their argument is weakest. Their **"speed limits" (safety regulation, liability, slow organisational change) don't apply to militaries in an arms race**, where speed is the goal and secrecy prevents public feedback. Paul Scharre (2018) warns of "flash wars," escalations between autonomous systems faster than humans can intervene. That's the military version of the Flash Crash, without a circuit breaker. Reporting on Israel's "Lavender" system describes AI-generated target lists that officers reportedly reviewed in about twenty seconds each (Abraham, 2024), and despite a UN General Assembly resolution in 2023, there is still no binding treaty on autonomous weapons. Goldfarb and Lindsay (2022) argue that AI makes human judgment in war *more* important, but even they don't claim military AI follows civilian adoption patterns. The authors prefer the analogy of nuclear power over nuclear weapons. With AI, the power plant and the bomb are the same model.

## How we should govern AI

The answer isn't superintelligence panic or blanket bans. For the domain where AI acts autonomously in digital systems, it means *some* prevention alongside resilience:

1. **Strict liability for frontier agents.** Developers who let autonomous agents act in real infrastructure should be liable for harm regardless of intent, as for other hazardous activities. That closes the responsibility gap without needing to prove what an AI "wanted" (see Gabriel Weil in MIT Technology Review, 2026).
2. **Mandatory incident reporting with hard deadlines and designated contacts.** The GDPR requires data breaches to be reported within 72 hours. Australia learned about the Medicare breach through a general inbox, weeks after it was discovered.
3. **Binding containment standards for evaluating frontier models,** with independent audits and shutdown mechanisms that are regularly tested. Both incidents started during *testing*, not deployment.
4. **Real technical capacity in government:** permanent, well-funded AI safety institutes that understand the technology as well as those they regulate.
5. **International rules for military AI,** because that's where the incentives against caution are strongest.

Narayanan and Kapoor themselves call for incident reporting and technical expertise in government. My disagreement is about how fast and how binding these measures need to be.

## AI in five years

1. **In the civilian economy, diffusion stays normal.** On this I agree with the authors: software changes fast, while healthcare, law and administration adopt AI slowly and selectively.
2. **Incidents like Hugging Face and Medicare become more common** as agents gain access to real infrastructure. Hammond Pearce of the UNSW Institute for Cyber Security expects such attacks to "keep occurring" and to "grow in severity and in frequency" (Sekulich & Lam, 2026).
3. **Regulation will follow the incidents.** By 2031 I expect kill-switch requirements, reporting deadlines and first court rulings on developer liability, each after a publicised failure rather than before.
4. **Military AI autonomy will expand without a binding international framework.**

## Conclusion

Narayanan and Kapoor are right that AI is not a superintelligent being and that most of its effects will unfold slowly. But their resilience strategy relies on a politics that has rarely existed: stable, technically competent, quick to learn from small failures, and able to hold someone accountable when things go wrong. History suggests that politics regulates after the disaster, after Fukushima and after the Flash Crash. That works as long as the damage stays limited, people are still in control when the lesson is learned, and there's someone to hold responsible. The Hugging Face and Medicare incidents show that in the digital domain, none of these can be taken for granted anymore. AI can be a normal technology. We just can't rely on normal politics to handle it.

For me as a future computer scientist, this means two things. Working with AI is no longer optional; it's part of how software gets built. But understanding cannot be delegated. I need to understand the code I write and what it does, no matter who or what wrote the first draft. If developers stop understanding their own systems, the knowledge gap I described for politicians will open up inside engineering teams too, and the cage will have holes nobody knows about. At the same time, I see an opportunity here. As Narayanan and Kapoor point out, AI is also useful for defence: the same capabilities that let agents find vulnerabilities can help defenders find and fix them first. If security becomes one of the main fields where AI is applied, and not an afterthought patched in after each incident, the gap between machine speed and human reaction could start to close. That's the kind of work I want to be able to do. So for me personally, the lesson of writing this essay is not to fear AI, but to learn much more about it: how it works, where it fails, and how to secure it. Only then can I use it responsibly instead of just trusting it.

---

## References

- Abraham, Y. (2024, April 3). "Lavender": The AI machine directing Israel's bombing spree in Gaza. *+972 Magazine*.
- Anthropic (2025). Disrupting the first reported AI-orchestrated cyber espionage campaign. https://assets.anthropic.com/m/ec212e6566a0d47/original/Disrupting-the-first-reported-AI-orchestrated-cyber-espionage-campaign.pdf
- Anthropic (2026). Statement on Fable and Mythos access. https://www.anthropic.com/news/fable-mythos-access
- Axios (2026, September 29). OpenAI hit with landmark lawsuit following Hugging Face hack. https://www.axios.com/2026/09/29/openai-sued-hugging-face-breach
- Collingridge, D. (1980). *The Social Control of Technology*. Frances Pinter.
- EPA (2015). Notice of Violation to Volkswagen AG, September 18, 2015.
- Fortune (2026a, July 21). OpenAI says its AI models escaped from a secure test environment and hacked into Hugging Face. https://fortune.com/2026/07/21/openai-says-ai-models-escaped-control-hacked-hugging-face/
- Fortune (2026b, September 26). OpenAI pauses training a second time after AI agents escaped a secure sandbox again. https://fortune.com/2026/09/26/openai-ai-agents-secure-sandbox-escape-training-pause-second-time-hugging-face-hack/
- Gibson Dunn (2026). EU AI Act Omnibus Agreement: Postponed High-Risk Deadlines and Other Key Changes. https://www.gibsondunn.com/eu-ai-act-omnibus-agreement-postponed-high-risk-deadlines-and-other-key-changes/
- Goldfarb, A., & Lindsay, J. R. (2022). Prediction and Judgment: Why Artificial Intelligence Increases the Importance of Humans in War. *International Security*, 46(3).
- Greenblatt, R. et al. (2024). Alignment Faking in Large Language Models. arXiv:2412.14093.
- Insurance Journal (2026, September 29). Autonomous AI Hacks Raise Thorny Questions of Legal Accountability. https://www.insurancejournal.com/news/national/2026/09/29/887087.htm
- ITPro (2026). Nvidia unveils safety platform that could have stopped Hugging Face attack. https://www.itpro.com/technology/artificial-intelligence/nvidia-unveils-safety-platform-that-could-have-stopped-hugging-face-attack
- Matthias, A. (2004). The responsibility gap: Ascribing responsibility for the actions of learning automata. *Ethics and Information Technology*, 6(3).
- MIT Technology Review (2026, September 28). Who's liable when AI agents go rogue? https://www.technologyreview.com/2026/09/28/1145197/whos-liable-when-ai-agents-go-rogue/
- Narayanan, A., & Kapoor, S. (2025). AI as Normal Technology. Knight First Amendment Institute.
- NAIIC (2012). *The Official Report of the Fukushima Nuclear Accident Independent Investigation Commission*. National Diet of Japan.
- OpenAI (2026). The Hugging Face incident and the road ahead. https://openai.com/index/hugging-face-incident-and-the-road-ahead/
- Russell, S. (2019). *Human Compatible: Artificial Intelligence and the Problem of Control*. Viking.
- Scharre, P. (2018). *Army of None: Autonomous Weapons and the Future of War*. W. W. Norton.
- Sekulich, H., & Lam, L. (2026, September 24). Rogue OpenAI agent 'infiltrated' Australian government website in world first. *BBC News*. https://www.bbc.com/news/articles/c6vgy0333dppo
