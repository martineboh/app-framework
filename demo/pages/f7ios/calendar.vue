<template>
  <div data-page="calendar" class="page kitchen-sink-ios">
    <div class="navbar">
      <div class="navbar-inner">
        <div class="left sliding"><a class="back link" href="#"><i class="icon icon-back"></i><span>Back</span></a></div>
        <div class="center sliding">Calendar</div>
      </div>
    </div>
    <div class="page-content">
      <div class="content-block">
        <p>Calendar is a touch optimized component that provides an easy way to handle dates.</p>
        <p>Calendar could be used as inline component or as overlay. Overlay Calendar will be automatically converted to Popover on tablets (iPad).</p>
      </div>
      <div class="content-block-title">Default setup</div>
      <div class="list-block">
        <ul>
          <li>
            <div class="item-content">
              <div class="item-inner">
                <div class="item-input">
                  <input type="text" placeholder="Your birth date" readonly="readonly" id="ks-calendar-default">
                </div>
              </div>
            </div>
          </li>
        </ul>
      </div>
      <div class="content-block-title">Custom date format</div>
      <div class="list-block">
        <ul>
          <li>
            <div class="item-content">
              <div class="item-inner">
                <div class="item-input">
                  <input type="text" placeholder="Select date" readonly="readonly" id="ks-calendar-date-format">
                </div>
              </div>
            </div>
          </li>
        </ul>
      </div>
      <div class="content-block-title">Multiple Values</div>
      <div class="list-block">
        <ul>
          <li>
            <div class="item-content">
              <div class="item-inner">
                <div class="item-input">
                  <input type="text" placeholder="Select multiple dates" readonly="readonly" id="ks-calendar-multiple">
                </div>
              </div>
            </div>
          </li>
        </ul>
      </div>
      <div class="content-block-title">Range Picker <span class="badge bg-green">NEW</span></div>
      <div class="list-block">
        <ul>
          <li>
            <div class="item-content">
              <div class="item-inner">
                <div class="item-input">
                  <input type="text" placeholder="Select date range" readonly="readonly" id="ks-calendar-range">
                </div>
              </div>
            </div>
          </li>
        </ul>
      </div>
      <div class="content-block-title">Inline with custom toolbar</div>
      <div class="content-block">
        <div style="padding:0; margin-right:-15px; width:auto" class="content-block-inner">
          <div id="ks-calendar-inline-container"></div>
        </div>
      </div>
    </div>
  </div>
</template>
