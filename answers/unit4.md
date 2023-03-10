# Week 7
## Synthesis Questions
### Vision Anatomy and Physiology
- Where in the brain do signals from the retina go before reaching the visual cortex?
	- Thalamus
- Describe the phenomena of retinal neurons that “get tired”. Do you think there are analogous processes in deep learning or convolutional neural networks?
	- Retinal neurons get tired after prolonged exposure to a particular visual stimulus, which makes them unresponsive to other stimuli.
	- The analogous process in DL and CNN would be overfitting. When a model is trained on a dataset with a specific stimulus, the model will become less responsive to other stimuli because it is fitted too well to the training dataset.


### Primary Visual Cortex
- What wavelengths of light can humans detect? Why might we only be able to detect such a narrow band of light wavelengths? What would be an advantage and downside of processing more?
	- 400-700nm
	- Narrow band because of the limited sensitivity of our photoreceptors (rods and cones)
	- Advantage of more: can perceive more colors and spectrums of light
	- Disadvantage of more: need more processing power in the brain
- What is V1 in the visual cortex? What are those cells most sensitive to?
	- First stop for visual information (primary visual cortex in the occipital lobe). About 2mm thick and highly organized: contains cortical columns, organized retinotopically, shows cortical magnification
	- Contains simple, complex, and end-stopped cells.
	- Most sensitive to bars or edges with narrow ranges of orientations.
- What is the fovea best at detecting?
	- It is the best at detecting details as it is in the center of our focus.
- Describe the retinotopic nature of the visual cortex (7:58) in your own words. Hypothesize whether convolutional neural networks might be organized as “retinotopic”.
	- The spatial mapping of features in retina is preserved in V1 where adjacent regions in the retina are also adjacent regions in V1.
	- Convolved data are kind of retinotopic because it preserves relative positions
- Describe cortical magnification and the causes of the trade-off between acuity and sensitivity. What are several reasons we can’t see details from extremely far away, as for example, hawks can?
	- Fixation point is magnified because the fovea has more photoreceptors and less convergence.
	- Leads to better acuity, focused feature will have high acuity
	- Tradeoff: better acuity at fovea, better sensitivity at periphery


### Functional Areas, Pathways, and Modules
- Describe at least 5 functional parts of the visual system
	- V1: primary visual cortex, handles easy features like edges
	- V4: on the back of the brain, handles color perception and perceiving the curvature of edges
	- MT: small, in the center, handles motion perception
	- Lateral occipital cortex and IT cortex: recognize complex shapes
	- Intraparietal sulcus: handles visually guided action like grasping
- What is the “what” stream? What does it do?
	- Ventral pathway (the bottom): V1&V2 -> V4 -> Inferotemporal Cortex
	- Transfers information about objects' identity like color and shape
- What is the “where” stream? What does it do?
	- Dorsal pathway (over the top): V1&V2 -> MT -> Parietal Cortex
	- Transfers information about objects' motion and location, and guided action
- What is a region that processes faces? What inputs does it receive? What other regions is it near?
	- Fusiform face area within the inferotemporal (IT) cortex
	- Near the parahippocampal place area and IT cortex
