---
layout: default
title: FUN STEAM IDEAS!
---

<style>
/* Hide the radio buttons */
.tabs input[type="radio"] {
    display: none;
}

/* Style the labels (the tabs themselves) */
.tabs label {
    padding: 10px 15px;
    cursor: pointer;
    border-bottom: 2px solid transparent;
    transition: border-color 0.3s ease;
}

/* Style the active tab label */
.tabs input[type="radio"]:checked + label {
    border-bottom-color: #007bff;
}

/* Hide all content panels by default */
.tab-panel {
    display: none;
}

/* Show the content panel associated with the active tab */
#tab1:checked ~ .tab-content#panel1,
#tab2:checked ~ .tab-content#panel2,
#tab3:checked ~ .tab-content#panel3,
#tab4:checked ~ .tab-content#panel4 {
    display: block;
}
</style>

<div class="tabs">
    <input type="radio" name="tab-group" id="tab1" checked>
    <label for="tab1">Home</label>
    <input type="radio" name="tab-group" id="tab2">
    <label for="tab2">Service</label>
    <input type="radio" name="tab-group" id="tab3">
    <label for="tab3">Other Resource</label>
    <input type="radio" name="tab-group" id="tab4">
    <label for="tab4">About Us</label>
    <div class="tab-panel" id="panel1">
        ## Welcome!
        <video width="720" height="405" controls muted="" autoplay="" loop="false">
            <source src="media/intro_video_short.mp4" type="video/mp4">
        </video>
    </div>
    <div class="tab-panel" id="tab2">
        ## Service
        Subscribe to our newsletter!
    </div>
    <div class="tab-panel" id="tab3">
        ## Other Resource
          ### Boston, MA
          ### Minneapolis, MN
          ### Dallas, TX
    </div>
    <div class="tab-panel" id="tab4">
        ## About us
        We are a team of parents, teachers and software engineers. 
    </div>
    
</div>
