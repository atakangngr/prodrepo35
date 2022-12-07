<template>
  <NucGridPage v-bind:gap="{'col':0,'row':0}" v-bind:rows="[1]"
    v-bind:schema="{'r0-c0':{'col':0,'row':0,'showIn':['xs','sm','md','lg'],'colSpan':1,'rowSpan':1}}"
    v-bind:columns="[1]" overflow="auto" v-bind:designMode="false" v-bind:minNsLimit="0"
    v-bind:style="{'background':'#FFFFFF','paddingTop':'0px','paddingLeft':'0px','paddingRight':'0px','paddingBottom':'0px'}">
    <NucGridCell v-bind:wrap="true" v-bind:reverse="false" overflow="hidden" direction="column"
      v-bind:showInDevice="['xs','sm','md','lg']" verticalAlignment="top" horizontalAlignment="left"
      id="33758ee8-4f07-4529-9188-ea7d170e4051" v-bind:col="0" v-bind:row="0" v-bind:colSpan="1" v-bind:rowSpan="1"
      v-bind:marginTop="0" v-bind:marginLeft="0" v-bind:marginRight="0" v-bind:marginBottom="0"
      v-bind:style="{'height':'auto','background':'transparent','paddingTop':'0px','borderColor':'','borderStyle':'solid','borderWidth':'0px','paddingLeft':'0px','borderRadius':'0px','paddingRight':'0px','paddingBottom':'0px','borderTopWidth':'0px','borderLeftWidth':'0px','borderRightWidth':'0px','borderBottomWidth':'0px','borderTopLeftRadius':'1px','borderTopRightRadius':'1px','borderBottomLeftRadius':'1px','borderBottomRightRadius':'1px'}"
      slot="r0-c0" area="r0-c0">
      <WBlockButton tag="button" href="" v-bind:pill="false" size="md" text="Block Level Button" type="button"
        v-bind:block="true" color="" theme="theme--light01" v-bind:squared="false" variant="primary"
        v-bind:isEnabled="true" background="" linkTarget="_self" ncLinkType="link" borderColor="007BFF"
        ncTypography="body1" v-bind:resetTrigger="false" ncTooltipText="" verticalWidth="60px"
        v-bind:nucalDataModel="{'type':'NSW','isList':false,'dynamic':false,'structure':[{'type':'string','propName':'text','displayName':'Value'}]}"
        verticalHeight="60px" horizontalWidth="72.4479px" toForRouterLink="to" horizontalHeight="37.5347px"
        ncClickFontColor="#FFFFFF" ncFocusFontColor="#FFFFFF" ncHoverFontColor="#FFFFFF" ncClickBorderColor="#007bff"
        ncDisableFontColor="#FFFFFF" ncFocusBorderColor="#007bff" ncHoverBorderColor="#007bff"
        ncDisableBorderColor="transparent" ncClickBackgroundColor="#007bff" ncFocusBackgroundColor="#007bff"
        ncHoverBackgroundColor="#007bff" ncDisableBackgroundColor="#969696" position="absolute" top="38.26901248581158%"
        left="0%" id="43944a65-c595-4cab-8268-34f189bde821"
        v-bind:style="{'width':'','height':'','fontSize':'9px','maxWidth':'','minWidth':'','tabIndex':'0px','boxShadow':'','fontStyle':'normal','marginTop':'0px','maxHeight':'','minHeight':'','textAlign':'center','fontFamily':'OpenSans-Bold,Open Sans','fontWeight':'bold','lineHeight':'1.0499999999999998','marginLeft':'0px','paddingTop':'','textShadow':'','visibility':'visible','borderStyle':'solid','marginRight':'0px','paddingLeft':'','marginBottom':'0px','paddingRight':'','paddingBottom':'','borderTopWidth':'0.75px','textDecoration':'none','borderLeftWidth':'0.75px','borderRightWidth':'0.75px','horizontalHeight':'28.151025px','borderBottomWidth':'0.75px','borderTopLeftRadius':'3px','borderTopRightRadius':'3px','borderBottomLeftRadius':'3px','borderBottomRightRadius':'3px','zIndex':2}"/>
    </NucGridCell>
  </NucGridPage>
</template>
<script>
export default {
  name: 'Screen1',
  data() {
    return {};
  },
  props: {},
  created() {},
  mounted() {},
  computed: {},
  methods: {},
  watch: {},
};
</script>

<style scoped></style>