=====================
SPECIFIC REQUIREMENTS
=====================

**External Interface requirements**
-----------------------------------
	**- User Interfaces**

		User interface must be user-friendly. The user interface shall be designed using various in-
		built components available in android 4.0.3 packages such as VideoView for playing lecture
		video, ExpandableListView to display the tree structure to navigate through the lecture
		video, SlidingDrawer for hiding and showing the content etc.

	**- Hardware Interfaces**

		- Any android operating system supported device
		- microSD-Card to view the lecture video.

	**- Software Interfaces**

		- Eclipse IDE shall be used as development environment for implementing the modules.
		- Designing of modules and diagrams is done in UML using MS word and smartDraw.

	**- Communications Interfaces**

		- WI-FI connectivity will be required to view lecture video present on the server.

**Functional Requirements**
---------------------------
	**- External role**

	 	**- User Student**

 			- Student Should be able to access lecture video from microSD-Card or Wi-Fi
 			- If student wants to access lecture video from Server , student tablet has to connected
			  with Access point

			- Same access point should be accessible by Server



**Behavioral Requirements**
---------------------------
	Behavioral requirements of the system are described using use case view.
	Following use case diagrams and DFDs summarize the functional and behavioral requirements
	of the proxyMITY tool:

		1. Use case diagram of the application
		2. Use case diagram to start the lecture video
		3. Use case diagram for bookmarking
		4. Use case diagram for viewing videos with subtitles
		5. Data Flow Diagram through SD-Card
		6. Data Flow through Server

.. image::
  https://raw.github.com/NileshSingh/proxyMITY_Document/master/images/usecase_application.png
Fig.1.

.. image::
  https://raw.github.com/NileshSingh/proxyMITY_Document/master/images/usecase_lecture.png
Fig 2.

.. image::
  https://raw.github.com/NileshSingh/proxyMITY_Document/master/images/bookmark.png
Fig.3.
		
.. image::
  https://raw.github.com/NileshSingh/proxyMITY_Document/master/images/subtitle.png
Fig4.
		
.. image::
  https://raw.github.com/NileshSingh/proxyMITY_Document/master/images/dfd1.png
Fig.5.
		
		
.. image::
  https://raw.github.com/NileshSingh/proxyMITY_Document/master/images/dfd2.png
Fig.6.

**Other Non-functional requirements**
-------------------------------------
	**Performance requirements**
		**- Capacity**

			proxyMITY shall support published lecture video to each students with microSD-
			Card and Wi-Fi support.

		**- Safety**

			The proxyMITY can play any video published lecture with android based player

**System quality attributes**
-----------------------------
		**- Accessibility**

			Any graphical user interfaces of the system shall use adequate font size to be usable
			by persons with limited visual capacity.

		**- Accuracy and precision**


			- Mp4 and 3gp format of lecture video can be played with proxyMITY tool.
			- All indexing of tree structure and tagging of topics is done by subject exp

















