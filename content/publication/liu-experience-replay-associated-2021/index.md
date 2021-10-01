---
title: "Experience replay is associated with efficient nonlocal learning"
date: 2021-05-01
publishDate: 2021-10-01T23:53:32.741740Z
authors: ["Yunzhe Liu", "Marcelo G. Mattar", "Timothy E. J. Behrens", "Nathaniel D. Daw", "Raymond J. Dolan"]
publication_types: ["2"]
abstract: "Replay supports planning Learning from direct experience is easy—we can always use trial and error—but how do we learn from nondirect (nonlocal) experiences? For this, we need additional mechanisms that bridge time and space. In rodents, hippocampal replay is hypothesized to promote this function. Liu et al. measured high-temporal-resolution brain signals using human magnetoencephalography combined with a new model-based, visually oriented, multipath reinforcement memory task. This task was designed to differentiate local versus nonlocal learning episodes within the subject. They found that reverse sequential replay in the human medial temporal lobe supports nonlocal reinforcement learning and is the underlying mechanism for solving complex credit assignment problems such as value learning. Science, abf1357, this issue p. eabf1357 Structured Abstract INTRODUCTIONAdaptive decision-making requires assimilation of reward information to guide subsequent choices. However, actions and outcomes are often separated by time and space, rendering this difficult. In reinforcement learning, this problem can be solved using “model-based” inference, in which an agent leverages a learned model of the environment to link local reward to nonlocal actions; this process is known as experience replay.A potential neural substrate for this process is hippocampal “replay.” In rodents, cells in the hippocampus fire in an organized manner that recapitulates past or potential future trajectories during rest. A similar phenomenon has also been observed in humans during a post-task rest period. However, a direct connection between replay and nonlocal (i.e., model-based) learning has yet to be established. RATIONALEThe question of how to achieve model-based learning in the service of adaptive behavior is central to understanding intelligence in both biological and artificial agents. We addressed this question by exploiting a normative model of replay based on reinforcement learning theory. This model makes specific predictions regarding how replay relates to nonlocal learning and about which information is more or less useful if replayed. To measure replay in humans, we used machine learning techniques in conjunction with magnetoencephalography (MEG) recordings of whole-brain neural activity. These techniques enabled us to ask whether and how neural replay contributes to nondirect learning in humans. In so doing, we address an outstanding question in reinforcement learning theory: how the brain forms links between disjoint actions and goals and uses these to inform better decisions in the future. RESULTSWe designed a novel decision-making task to separate local from nonlocal learning—that is, learning from direct experience as opposed to indirect learning based on inference. Specifically, we developed a three-arm task, wherein each arm comprised two paths leading to distinct end states. Crucially, the two end states, reachable from each arm, are shared across all three arms. This design feature allows post-choice reward feedback to inform future choices not only in the chosen arm (local learning) but also in either of the other two arms (nonlocal learning).This work revealed the existence of backward neural replay of nonlocal experiences after reward receipt, with a 160-ms state-to-state time lag. In line with normative theory, such replay predominantly represents the path most useful for future behavior. This backward replay encoded nonlocal experience alone and was physiologically distinct from a faster forward replay (30-ms time lag), which was associated with power increase in a ripple band.Using computational modeling, we showed that the strength of this backward replay relates to efficient trial-by-trial within-subject learning of the same nonlocal experience, as well as a better overall task performance across subjects. This is consistent with our theoretical predictions and provides strong support for a reinforcement learning–based account of neural replay in decision-making. CONCLUSIONBackward replay accompanies efficient nonlocal learning in humans and is prioritized according to its utility. These results connect several findings in human and rodent neuroscience and implicate experience replay in model-based reinforcement learning. textlessimg class=\"fragment-image\" aria-describedby=\"F1-caption\" src=\"https://science.sciencemag.org/content/sci/372/6544/eabf1357/F1.medium.gif\"/textgreater Download high-res image Open in new tab Download Powerpoint Experience replay is associated with efficient nonlocal learning.Top left: The key element of the experimental design is a separation of local versus nonlocal learning. The chosen path (indicated by hand) reflects local experience; the other two paths leading to the same outcome state (the red £), but not directly experienced, are the nonlocal paths. Arrow direction indicates the order of actual experience; color indicates the arm identity. There are three arms, and outcomes are shared across the three arms. Top right: Nonlocal backward replay after reward receipt. There are two nonlocal experiences per trial. We found neural replay of these paths after reward receipt, consistent with a credit assignment account in reinforcement learning—an assignment of local reward information to nonlocal actions. Bottom: Consistent with reinforcement learning theory, replay was prioritized according to utility (need × gain) and was related to more efficient nonlocal learning. In the example, this is illustrated as stronger replay (double arrows) for the green path, because of its higher utility (0.32 versus 0.29) relative to the orange path. To make effective decisions, people need to consider the relationship between actions and outcomes. These are often separated by time and space. The neural mechanisms by which disjoint actions and outcomes are linked remain unknown. One promising hypothesis involves neural replay of nonlocal experience. Using a task that segregates direct from indirect value learning, combined with magnetoencephalography, we examined the role of neural replay in human nonlocal learning. After receipt of a reward, we found significant backward replay of nonlocal experience, with a 160-millisecond state-to-state time lag, which was linked to efficient learning of action values. Backward replay and behavioral evidence of nonlocal learning were more pronounced for experiences of greater benefit for future behavior. These findings support nonlocal replay as a neural mechanism for solving complex credit assignment problems during learning. Reverse sequential replay supports nondirect reinforcement learning in humans and is prioritized according to utility. Reverse sequential replay supports nondirect reinforcement learning in humans and is prioritized according to utility."
featured: false
publication: "*Science*"
url_pdf: "https://science.sciencemag.org/content/372/6544/eabf1357"
doi: "10.1126/science.abf1357"
---
