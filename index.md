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
#tab1:checked ~ #panel1,
#tab2:checked ~ #tab2-panel,
#tab3:checked ~ #tab3-panel,
#tab4:checked ~ #tab4-panel {
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
        <h2> Welcome! </h2> <br /><br />
        <video width="720" height="405" controls muted="" autoplay="" loop="false">
            <source src="media/intro_video_short.mp4" type="video/mp4">
        </video>
    </div>
    <div class="tab-panel" id="tab2-panel">
        <h2> Service </h2> <br /><br />
        Subscribe to our newsletter!
    </div>
    <div class="tab-panel" id="tab3-panel">
        <h2> Other Resource </h2> <br /><br />
          <h3> Boston, MA </h3><br /><br />
          <h3> Minneapolis, MN </h3><br /><br />
          <h3> Dallas, TX  </h3><br /><br />
    </div>
    <div class="tab-panel" id="tab4-panel">
        <h2> About us </h2> <br /><br />
        <p> 
            We are a team of parents, teachers and software engineers.
        </p> 
    </div>
    
</div>
