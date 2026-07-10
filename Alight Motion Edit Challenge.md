<?xml version='1.0' encoding='UTF-8' ?>
<!-- TikTok edit remake base: zoom + flash + shake + glitch system -->
<scene title="TikTok Edit Remake Base" width="1080" height="1080" exportWidth="1920" exportHeight="1080" bgcolor="#FF000000" totalTime="18500" fps="60" modifiedTime="0" amver="859" ffver="107" am="com.alightcreative.motion/6.2.53" amplatform="ios" precompose="dynamicResolution" retime="freeze">

  <!-- Replace these with your own imported clips/images -->
  <media uri="am-internal:///REPLACE_CLIP_01.MP4" type="video/mp4" duration="2597" size="0" fps="60" width="1080" height="1080"/>
  <media uri="am-internal:///REPLACE_CLIP_02.MP4" type="video/mp4" duration="2650" size="0" fps="60" width="1080" height="1080"/>
  <media uri="am-internal:///REPLACE_CLIP_03.MP4" type="video/mp4" duration="1766" size="0" fps="60" width="1080" height="1080"/>
  <media uri="am-internal:///REPLACE_CLIP_04.MP4" type="video/mp4" duration="1483" size="0" fps="60" width="1080" height="1080"/>
  <media uri="am-internal:///REPLACE_CLIP_05.MP4" type="video/mp4" duration="1999" size="0" fps="60" width="1080" height="1080"/>
  <media uri="am-internal:///REPLACE_CLIP_06.MP4" type="video/mp4" duration="1999" size="0" fps="60" width="1080" height="1080"/>
  <media uri="am-internal:///REPLACE_CLIP_07.MP4" type="video/mp4" duration="2166" size="0" fps="60" width="1080" height="1080"/>

  <!-- Base background -->
  <shape id="1" startTime="0" endTime="18500" fillType="color" s=".rect">
    <transform>
      <location value="540.000000,540.000000,0.000000"/>
      <scale value="5.400000,5.400000"/>
    </transform>
    <fillColor value="#FF000000"/>
  </shape>

  <!-- Segment 1: intro close-up -->
  <shape id="2" startTime="0" endTime="2597" fillType="media" fillVideo="am-internal:///REPLACE_CLIP_01.MP4" mediaFillMode="fill" s=".rect">
    <transform>
      <location value="540.000000,540.000000,0.000000"/>
      <scale>
        <kf t="0.000000" v="0.930000,0.930000"/>
        <kf t="0.420000" v="1.140000,1.140000" e="cubicBezier 0.18 0.0 0.20 1.0"/>
        <kf t="0.760000" v="1.050000,1.050000" e="cubicBezier 0.0 0.0 0.58 1.0"/>
        <kf t="0.985000" v="1.220000,1.220000" e="cubicBezier 0.42 0.0 1.0 0.42"/>
      </scale>
      <rotation>
        <kf t="0.000000" v="-1.400000"/>
        <kf t="0.500000" v="0.900000"/>
        <kf t="0.985000" v="0.000000"/>
      </rotation>
    </transform>
    <effect id="com.alightcreative.effects.tile" locallyApplied="true">
      <property name="mirror" type="bool" value="true"/>
      <property name="scale" type="float" value="1.010000"/>
    </effect>
    <effect id="com.alightcreative.effects.motionblur4" locallyApplied="true">
      <property name="tune" type="float">
        <kf t="0.000000" v="2.700000"/>
        <kf t="0.800000" v="1.000000"/>
        <kf t="1.000000" v="0.000000"/>
      </property>
    </effect>
    <effect id="com.alightcreative.effects.oscillate3" locallyApplied="true">
      <property name="angle" type="float">
        <kf t="0.000000" v="6.000000"/>
        <kf t="0.968992" v="190.000000"/>
      </property>
      <property name="freq" type="float" value="2.500000"/>
      <property name="mag" type="float">
        <kf t="0.000000" v="90.000000"/>
        <kf t="0.968992" v="28.000000"/>
      </property>
      <property name="phase" type="float" value="0.500000"/>
    </effect>
    <property name="size" type="vec2" value="540.000000,540.000000"/>
  </shape>

  <!-- Flash cut -->
  <shape id="3" startTime="2460" endTime="2597" fillType="color" s=".rect">
    <transform>
      <location value="540.000000,540.000000,0.000000"/>
      <scale value="5.400000,5.400000"/>
    </transform>
    <fillColor value="#FFFFFFFF"/>
    <effect id="com.alightcreative.effects.fade" locallyApplied="true">
      <property name="inTime" type="float" value="0.020000"/>
      <property name="outTime" type="float" value="0.020000"/>
    </effect>
  </shape>

  <!-- Segment 2: stronger zoom + soft shake -->
  <shape id="4" startTime="2584" endTime="5234" fillType="media" fillVideo="am-internal:///REPLACE_CLIP_02.MP4" mediaFillMode="fill" s=".rect">
    <transform>
      <location value="540.000000,540.000000,0.000000"/>
      <scale>
        <kf t="0.000000" v="1.000000,1.000000"/>
        <kf t="0.320000" v="1.290000,1.290000" e="cubicBezier 0.0 0.0 0.58 1.0"/>
        <kf t="0.720000" v="1.080000,1.080000" e="cubicBezier 0.42 0.0 1.0 1.0"/>
        <kf t="0.985000" v="1.350000,1.350000" e="cubicBezier 0.42 0.0 1.0 0.42"/>
      </scale>
      <rotation>
        <kf t="0.000000" v="0.500000"/>
        <kf t="0.500000" v="-0.800000"/>
        <kf t="0.985000" v="0.000000"/>
      </rotation>
    </transform>
    <effect id="com.alightcreative.effects.tile" locallyApplied="true">
      <property name="mirror" type="bool" value="true"/>
      <property name="scale" type="float" value="1.008000"/>
    </effect>
    <effect id="com.alightcreative.effects.motionblur4" locallyApplied="true">
      <property name="tune" type="float">
        <kf t="0.000000" v="2.300000"/>
        <kf t="0.820000" v="1.100000"/>
        <kf t="1.000000" v="0.000000"/>
      </property>
    </effect>
    <effect id="com.alightcreative.effects.oscillate3" locallyApplied="true">
      <property name="angle" type="float">
        <kf t="0.000000" v="5.800000"/>
        <kf t="0.968992" v="200.000000"/>
      </property>
      <property name="freq" type="float" value="2.500000"/>
      <property name="mag" type="float">
        <kf t="0.000000" v="100.000000"/>
        <kf t="0.968992" v="30.000000"/>
      </property>
      <property name="phase" type="float" value="0.500000"/>
    </effect>
    <property name="size" type="vec2" value="540.000000,540.000000"/>
  </shape>

  <!-- Segment 3: glitch/white hit -->
  <shape id="5" startTime="5234" endTime="7000" fillType="media" fillVideo="am-internal:///REPLACE_CLIP_03.MP4" mediaFillMode="fill" s=".rect">
    <transform>
      <location value="540.000000,540.000000,0.000000"/>
      <scale>
        <kf t="0.000000" v="0.970000,0.970000"/>
        <kf t="0.400000" v="1.200000,1.200000" e="cubicBezier 0.0 0.0 0.58 1.0"/>
        <kf t="0.770000" v="1.050000,1.050000"/>
        <kf t="0.985000" v="1.300000,1.300000" e="cubicBezier 0.42 0.0 1.0 0.42"/>
      </scale>
    </transform>
    <effect id="com.alightcreative.effects.gaussianblur" locallyApplied="true">
      <property name="strength" type="float" value="0.080000"/>
    </effect>
    <effect id="com.alightcreative.effects.exposure" locallyApplied="true">
      <property name="exposure" type="float">
        <kf t="0.000000" v="0.000000"/>
        <kf t="0.500000" v="1.100000"/>
        <kf t="0.800000" v="0.000000"/>
      </property>
    </effect>
    <effect id="com.alightcreative.effects.spectralmap" locallyApplied="true">
      <property name="redColor" type="color" value="#FFFFFFFF"/>
      <property name="greenColor" type="color" value="#FFB349CD"/>
      <property name="blueColor" type="color" value="#FF881ED9"/>
      <property name="phase" type="float" value="-0.010000"/>
      <property name="repeat" type="float" value="10.000000"/>
      <property name="reverse" type="bool" value="true"/>
    </effect>
    <effect id="com.alightcreative.effects.motionblur4" locallyApplied="true">
      <property name="tune" type="float" value="2.000000"/>
    </effect>
    <property name="size" type="vec2" value="540.000000,540.000000"/>
  </shape>

  <!-- Segment 4: darker purple hit -->
  <shape id="6" startTime="7000" endTime="8483" fillType="media" fillVideo="am-internal:///REPLACE_CLIP_04.MP4" mediaFillMode="fill" s=".rect">
    <transform>
      <location value="540.000000,540.000000,0.000000"/>
      <scale>
        <kf t="0.000000" v="1.000000,1.000000"/>
        <kf t="0.420000" v="1.180000,1.180000" e="cubicBezier 0.18 0.0 0.20 1.0"/>
        <kf t="0.985000" v="1.020000,1.020000"/>
      </scale>
    </transform>
    <effect id="com.alightcreative.effects.tile" locallyApplied="true">
      <property name="mirror" type="bool" value="true"/>
    </effect>
    <effect id="com.alightcreative.effects.fractalwarp4" locallyApplied="false">
      <property name="intensity" type="float" value="0.650000"/>
      <property name="mag" type="float" value="0.075000"/>
      <property name="octaves" type="float" value="2.000000"/>
      <property name="scale" type="float" value="3.000000"/>
      <property name="screenSpace" type="bool" value="true"/>
    </effect>
    <effect id="com.alightcreative.effects.motionblur4" locallyApplied="true">
      <property name="tune" type="float" value="1.800000"/>
    </effect>
    <property name="size" type="vec2" value="540.000000,540.000000"/>
  </shape>

  <!-- Segment 5: halo / ring moment -->
  <shape id="7" startTime="8484" endTime="10483" fillType="media" fillVideo="am-internal:///REPLACE_CLIP_05.MP4" mediaFillMode="fill" s=".rect">
    <transform>
      <location value="540.000000,540.000000,0.000000"/>
      <scale>
        <kf t="0.000000" v="0.920000,0.920000"/>
        <kf t="0.350000" v="1.240000,1.240000" e="cubicBezier 0.0 0.0 0.58 1.0"/>
        <kf t="0.850000" v="1.060000,1.060000"/>
      </scale>
    </transform>
    <effect id="com.alightcreative.effects.ridges2" locallyApplied="false">
      <property name="octaves" type="float" value="3.000000"/>
      <property name="scale" type="float" value="0.690000"/>
      <property name="stretch" type="vec2" value="0.660000,1.000000"/>
    </effect>
    <effect id="com.alightcreative.effects.motionblur4" locallyApplied="true">
      <property name="tune" type="float" value="2.400000"/>
    </effect>
    <effect id="com.alightcreative.effects.softglow" locallyApplied="false">
      <property name="blend" type="float" value="0.000000"/>
      <property name="outsideAlpha" type="float" value="0.280000"/>
      <property name="strength" type="float" value="0.220000"/>
    </effect>
    <property name="size" type="vec2" value="540.000000,540.000000"/>
  </shape>

  <!-- Segment 6: high-energy split feel -->
  <shape id="8" startTime="10484" endTime="13083" fillType="media" fillVideo="am-internal:///REPLACE_CLIP_06.MP4" mediaFillMode="fill" s=".rect">
    <transform>
      <location value="540.000000,540.000000,0.000000"/>
      <pivot value="0.000000,-332.500000"/>
      <scale>
        <kf t="0.000000" v="1.000000,1.000000"/>
        <kf t="0.485000" v="1.480000,1.480000" e="cubicBezier 0.0 0.58 0.58 1.0"/>
        <kf t="0.975000" v="1.000000,1.000000" e="cubicBezier 0.42 0.0 1.0 0.42"/>
      </scale>
    </transform>
    <effect id="com.alightcreative.effects.tile" locallyApplied="true">
      <property name="mirror" type="bool" value="true"/>
    </effect>
    <effect id="com.alightcreative.effects.motionblur4" locallyApplied="true">
      <property name="tune" type="float" value="2.700000"/>
    </effect>
    <effect id="com.alightcreative.effects.shake2" locallyApplied="true">
      <property name="evolution" type="float" value="0.000000"/>
      <property name="freq" type="float" value="5.000000"/>
      <property name="mag" type="float" value="85.000000"/>
    </effect>
    <property name="size" type="vec2" value="540.000000,540.000000"/>
  </shape>

  <!-- Segment 7: final main cut -->
  <shape id="9" startTime="13084" endTime="18500" fillType="media" fillVideo="am-internal:///REPLACE_CLIP_07.MP4" mediaFillMode="fill" s=".rect">
    <transform>
      <location value="540.000000,540.000000,0.000000"/>
      <scale>
        <kf t="0.000000" v="1.000000,1.000000"/>
        <kf t="0.330000" v="1.180000,1.180000" e="cubicBezier 0.0 0.0 0.58 1.0"/>
        <kf t="0.720000" v="1.040000,1.040000"/>
        <kf t="0.985000" v="1.260000,1.260000" e="cubicBezier 0.42 0.0 1.0 0.42"/>
      </scale>
      <rotation>
        <kf t="0.000000" v="0.000000"/>
        <kf t="0.500000" v="1.200000"/>
        <kf t="0.985000" v="0.000000"/>
      </rotation>
    </transform>
    <effect id="com.alightcreative.effects.tile" locallyApplied="true">
      <property name="mirror" type="bool" value="true"/>
      <property name="scale" type="float" value="1.005000"/>
    </effect>
    <effect id="com.alightcreative.effects.motionblur4" locallyApplied="true">
      <property name="tune" type="float">
        <kf t="0.000000" v="2.200000"/>
        <kf t="0.800000" v="1.000000"/>
        <kf t="1.000000" v="0.000000"/>
      </property>
    </effect>
    <effect id="com.alightcreative.effects.oscillate3" locallyApplied="true">
      <property name="angle" type="float">
        <kf t="0.000000" v="200.000000"/>
        <kf t="1.000000" v="0.000000"/>
      </property>
      <property name="freq" type="float" value="2.500000"/>
      <property name="mag" type="float">
        <kf t="0.000000" v="100.000000"/>
        <kf t="1.000000" v="0.000000"/>
      </property>
    </effect>
    <property name="size" type="vec2" value="540.000000,540.000000"/>
  </shape>

  <!-- Beat flash overlays -->
  <shape id="10" startTime="1500" endTime="1565" fillType="color" s=".rect">
    <transform>
      <location value="540.000000,540.000000,0.000000"/>
      <scale value="5.400000,5.400000"/>
    </transform>
    <fillColor value="#FFFFFFFF"/>
    <effect id="com.alightcreative.effects.fade" locallyApplied="true">
      <property name="inTime" type="float" value="0.000000"/>
      <property name="outTime" type="float" value="0.040000"/>
    </effect>
  </shape>

  <shape id="11" startTime="6880" endTime="6945" fillType="color" s=".rect">
    <transform>
      <location value="540.000000,540.000000,0.000000"/>
      <scale value="5.400000,5.400000"/>
    </transform>
    <fillColor value="#FFFFFFFF"/>
    <effect id="com.alightcreative.effects.fade" locallyApplied="true">
      <property name="inTime" type="float" value="0.000000"/>
      <property name="outTime" type="float" value="0.040000"/>
    </effect>
  </shape>

  <shape id="12" startTime="10420" endTime="10492" fillType="color" s=".rect">
    <transform>
      <location value="540.000000,540.000000,0.000000"/>
      <scale value="5.400000,5.400000"/>
    </transform>
    <fillColor value="#FFFFFFFF"/>
    <effect id="com.alightcreative.effects.fade" locallyApplied="true">
      <property name="inTime" type="float" value="0.000000"/>
      <property name="outTime" type="float" value="0.030000"/>
    </effect>
  </shape>

  <!-- Dark end fade -->
  <shape id="13" startTime="17350" endTime="18500" fillType="color" s=".rect">
    <transform>
      <location value="540.000000,540.000000,0.000000"/>
      <scale value="5.400000,5.400000"/>
      <opacity>
        <kf t="0.000000" v="0.000000"/>
        <kf t="1.000000" v="0.900000" e="cubicBezier 0.42 0.0 1.0 1.0"/>
      </opacity>
    </transform>
    <fillColor value="#FF000000"/>
  </shape>

</scene>
