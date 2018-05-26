---
title: Module waf
---

<a href="..">@pulumi/aws</a>

<h2 class="pdoc-module-header">Index</h2>

* <a href="#ByteMatchSet">class ByteMatchSet</a>
* <a href="#GeoMatchSet">class GeoMatchSet</a>
* <a href="#IpSet">class IpSet</a>
* <a href="#RateBasedRule">class RateBasedRule</a>
* <a href="#RegexMatchSet">class RegexMatchSet</a>
* <a href="#RegexPatternSet">class RegexPatternSet</a>
* <a href="#Rule">class Rule</a>
* <a href="#RuleGroup">class RuleGroup</a>
* <a href="#SizeConstraintSet">class SizeConstraintSet</a>
* <a href="#SqlInjectionMatchSet">class SqlInjectionMatchSet</a>
* <a href="#WebAcl">class WebAcl</a>
* <a href="#XssMatchSet">class XssMatchSet</a>
* <a href="#ByteMatchSetArgs">interface ByteMatchSetArgs</a>
* <a href="#ByteMatchSetState">interface ByteMatchSetState</a>
* <a href="#GeoMatchSetArgs">interface GeoMatchSetArgs</a>
* <a href="#GeoMatchSetState">interface GeoMatchSetState</a>
* <a href="#IpSetArgs">interface IpSetArgs</a>
* <a href="#IpSetState">interface IpSetState</a>
* <a href="#RateBasedRuleArgs">interface RateBasedRuleArgs</a>
* <a href="#RateBasedRuleState">interface RateBasedRuleState</a>
* <a href="#RegexMatchSetArgs">interface RegexMatchSetArgs</a>
* <a href="#RegexMatchSetState">interface RegexMatchSetState</a>
* <a href="#RegexPatternSetArgs">interface RegexPatternSetArgs</a>
* <a href="#RegexPatternSetState">interface RegexPatternSetState</a>
* <a href="#RuleArgs">interface RuleArgs</a>
* <a href="#RuleGroupArgs">interface RuleGroupArgs</a>
* <a href="#RuleGroupState">interface RuleGroupState</a>
* <a href="#RuleState">interface RuleState</a>
* <a href="#SizeConstraintSetArgs">interface SizeConstraintSetArgs</a>
* <a href="#SizeConstraintSetState">interface SizeConstraintSetState</a>
* <a href="#SqlInjectionMatchSetArgs">interface SqlInjectionMatchSetArgs</a>
* <a href="#SqlInjectionMatchSetState">interface SqlInjectionMatchSetState</a>
* <a href="#WebAclArgs">interface WebAclArgs</a>
* <a href="#WebAclState">interface WebAclState</a>
* <a href="#XssMatchSetArgs">interface XssMatchSetArgs</a>
* <a href="#XssMatchSetState">interface XssMatchSetState</a>

<a href="/waf/byteMatchSet.ts">waf/byteMatchSet.ts</a> <a href="/waf/geoMatchSet.ts">waf/geoMatchSet.ts</a> <a href="/waf/ipSet.ts">waf/ipSet.ts</a> <a href="/waf/rateBasedRule.ts">waf/rateBasedRule.ts</a> <a href="/waf/regexMatchSet.ts">waf/regexMatchSet.ts</a> <a href="/waf/regexPatternSet.ts">waf/regexPatternSet.ts</a> <a href="/waf/rule.ts">waf/rule.ts</a> <a href="/waf/ruleGroup.ts">waf/ruleGroup.ts</a> <a href="/waf/sizeConstraintSet.ts">waf/sizeConstraintSet.ts</a> <a href="/waf/sqlInjectionMatchSet.ts">waf/sqlInjectionMatchSet.ts</a> <a href="/waf/webAcl.ts">waf/webAcl.ts</a> <a href="/waf/xssMatchSet.ts">waf/xssMatchSet.ts</a> 

<h2 class="pdoc-module-header">Modules</h2>


<h2 class="pdoc-module-header" id="ByteMatchSet">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-aws/blob/master/pack/nodejs/waf/byteMatchSet.ts#L9">class ByteMatchSet</a>
</h2>

Provides a WAF Byte Match Set Resource

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/pack/nodejs/waf/byteMatchSet.ts#L31">constructor</a>
</h3>

```typescript
new ByteMatchSet(name: string, args?: ByteMatchSetArgs, opts?: pulumi.ResourceOptions)
```


Create a ByteMatchSet resource with the given unique name, arguments, and options.

* `name` The _unique_ name of the resource.
* `args` The arguments to use to populate this resource&#39;s properties.
* `opts` A bag of options that control this resource&#39;s behavior.


```typescript
new ByteMatchSet(name: string, state?: ByteMatchSetState, opts?: pulumi.ResourceOptions)
```


Create a ByteMatchSet resource with the given unique name, arguments, and options.

* `name` The _unique_ name of the resource.
* `state` The state to use when looking up an instance of this resource.
* `opts` A bag of options that control this resource&#39;s behavior.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/pack/nodejs/waf/byteMatchSet.ts#L18">method get</a>
</h3>

```typescript
public static get(name: string, id: pulumi.Input<pulumi.ID>, state?: ByteMatchSetState): ByteMatchSet
```


Get an existing ByteMatchSet resource's state with the given name, ID, and optional extra
properties used to qualify the lookup.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/pack/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L72">method isInstance</a>
</h3>

```typescript
static isInstance(obj: any): boolean
```


Returns true if the given object is an instance of CustomResource.  This is designed to work even when
multiple copies of the Pulumi SDK have been loaded into the same process.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/pack/nodejs/waf/byteMatchSet.ts#L27">property byteMatchTuples</a>
</h3>

```typescript
public byteMatchTuples: pulumi.Output<{ ... }[] | undefined>;
```


Specifies the bytes (typically a string that corresponds
with ASCII characters) that you want to search for in web requests,
the location in requests that you want to search, and other settings.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/pack/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L67">property id</a>
</h3>

```typescript
id: Output<ID>;
```


id is the provider-assigned unique ID for this managed resource.  It is set during
deployments and may be missing (undefined) during planning phases.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/pack/nodejs/waf/byteMatchSet.ts#L31">property name</a>
</h3>

```typescript
public name: pulumi.Output<string>;
```


The name or description of the Byte Match Set.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/pack/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L15">property urn</a>
</h3>

```typescript
urn: Output<URN>;
```


urn is the stable logical URN used to distinctly address a resource, both before and after
deployments.

<h2 class="pdoc-module-header" id="GeoMatchSet">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-aws/blob/master/pack/nodejs/waf/geoMatchSet.ts#L9">class GeoMatchSet</a>
</h2>

Provides a WAF Geo Match Set Resource

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/pack/nodejs/waf/geoMatchSet.ts#L29">constructor</a>
</h3>

```typescript
new GeoMatchSet(name: string, args?: GeoMatchSetArgs, opts?: pulumi.ResourceOptions)
```


Create a GeoMatchSet resource with the given unique name, arguments, and options.

* `name` The _unique_ name of the resource.
* `args` The arguments to use to populate this resource&#39;s properties.
* `opts` A bag of options that control this resource&#39;s behavior.


```typescript
new GeoMatchSet(name: string, state?: GeoMatchSetState, opts?: pulumi.ResourceOptions)
```


Create a GeoMatchSet resource with the given unique name, arguments, and options.

* `name` The _unique_ name of the resource.
* `state` The state to use when looking up an instance of this resource.
* `opts` A bag of options that control this resource&#39;s behavior.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/pack/nodejs/waf/geoMatchSet.ts#L18">method get</a>
</h3>

```typescript
public static get(name: string, id: pulumi.Input<pulumi.ID>, state?: GeoMatchSetState): GeoMatchSet
```


Get an existing GeoMatchSet resource's state with the given name, ID, and optional extra
properties used to qualify the lookup.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/pack/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L72">method isInstance</a>
</h3>

```typescript
static isInstance(obj: any): boolean
```


Returns true if the given object is an instance of CustomResource.  This is designed to work even when
multiple copies of the Pulumi SDK have been loaded into the same process.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/pack/nodejs/waf/geoMatchSet.ts#L25">property geoMatchConstraints</a>
</h3>

```typescript
public geoMatchConstraints: pulumi.Output<{ ... }[] | undefined>;
```


The GeoMatchConstraint objects which contain the country that you want AWS WAF to search for.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/pack/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L67">property id</a>
</h3>

```typescript
id: Output<ID>;
```


id is the provider-assigned unique ID for this managed resource.  It is set during
deployments and may be missing (undefined) during planning phases.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/pack/nodejs/waf/geoMatchSet.ts#L29">property name</a>
</h3>

```typescript
public name: pulumi.Output<string>;
```


The name or description of the GeoMatchSet.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/pack/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L15">property urn</a>
</h3>

```typescript
urn: Output<URN>;
```


urn is the stable logical URN used to distinctly address a resource, both before and after
deployments.

<h2 class="pdoc-module-header" id="IpSet">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-aws/blob/master/pack/nodejs/waf/ipSet.ts#L9">class IpSet</a>
</h2>

Provides a WAF IPSet Resource

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/pack/nodejs/waf/ipSet.ts#L30">constructor</a>
</h3>

```typescript
new IpSet(name: string, args?: IpSetArgs, opts?: pulumi.ResourceOptions)
```


Create a IpSet resource with the given unique name, arguments, and options.

* `name` The _unique_ name of the resource.
* `args` The arguments to use to populate this resource&#39;s properties.
* `opts` A bag of options that control this resource&#39;s behavior.


```typescript
new IpSet(name: string, state?: IpSetState, opts?: pulumi.ResourceOptions)
```


Create a IpSet resource with the given unique name, arguments, and options.

* `name` The _unique_ name of the resource.
* `state` The state to use when looking up an instance of this resource.
* `opts` A bag of options that control this resource&#39;s behavior.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/pack/nodejs/waf/ipSet.ts#L18">method get</a>
</h3>

```typescript
public static get(name: string, id: pulumi.Input<pulumi.ID>, state?: IpSetState): IpSet
```


Get an existing IpSet resource's state with the given name, ID, and optional extra
properties used to qualify the lookup.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/pack/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L72">method isInstance</a>
</h3>

```typescript
static isInstance(obj: any): boolean
```


Returns true if the given object is an instance of CustomResource.  This is designed to work even when
multiple copies of the Pulumi SDK have been loaded into the same process.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/pack/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L67">property id</a>
</h3>

```typescript
id: Output<ID>;
```


id is the provider-assigned unique ID for this managed resource.  It is set during
deployments and may be missing (undefined) during planning phases.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/pack/nodejs/waf/ipSet.ts#L26">property ipSetDescriptors</a>
</h3>

```typescript
public ipSetDescriptors: pulumi.Output<{ ... }[] | undefined>;
```


Specifies the IP address type (IPV4 or IPV6)
and the IP address range (in CIDR format) that web requests originate from.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/pack/nodejs/waf/ipSet.ts#L30">property name</a>
</h3>

```typescript
public name: pulumi.Output<string>;
```


The name or description of the IPSet.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/pack/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L15">property urn</a>
</h3>

```typescript
urn: Output<URN>;
```


urn is the stable logical URN used to distinctly address a resource, both before and after
deployments.

<h2 class="pdoc-module-header" id="RateBasedRule">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-aws/blob/master/pack/nodejs/waf/rateBasedRule.ts#L9">class RateBasedRule</a>
</h2>

Provides a WAF Rate Based Rule Resource

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/pack/nodejs/waf/rateBasedRule.ts#L41">constructor</a>
</h3>

```typescript
new RateBasedRule(name: string, args: RateBasedRuleArgs, opts?: pulumi.ResourceOptions)
```


Create a RateBasedRule resource with the given unique name, arguments, and options.

* `name` The _unique_ name of the resource.
* `args` The arguments to use to populate this resource&#39;s properties.
* `opts` A bag of options that control this resource&#39;s behavior.


```typescript
new RateBasedRule(name: string, state?: RateBasedRuleState, opts?: pulumi.ResourceOptions)
```


Create a RateBasedRule resource with the given unique name, arguments, and options.

* `name` The _unique_ name of the resource.
* `state` The state to use when looking up an instance of this resource.
* `opts` A bag of options that control this resource&#39;s behavior.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/pack/nodejs/waf/rateBasedRule.ts#L18">method get</a>
</h3>

```typescript
public static get(name: string, id: pulumi.Input<pulumi.ID>, state?: RateBasedRuleState): RateBasedRule
```


Get an existing RateBasedRule resource's state with the given name, ID, and optional extra
properties used to qualify the lookup.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/pack/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L72">method isInstance</a>
</h3>

```typescript
static isInstance(obj: any): boolean
```


Returns true if the given object is an instance of CustomResource.  This is designed to work even when
multiple copies of the Pulumi SDK have been loaded into the same process.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/pack/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L67">property id</a>
</h3>

```typescript
id: Output<ID>;
```


id is the provider-assigned unique ID for this managed resource.  It is set during
deployments and may be missing (undefined) during planning phases.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/pack/nodejs/waf/rateBasedRule.ts#L25">property metricName</a>
</h3>

```typescript
public metricName: pulumi.Output<string>;
```


The name or description for the Amazon CloudWatch metric of this rule.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/pack/nodejs/waf/rateBasedRule.ts#L29">property name</a>
</h3>

```typescript
public name: pulumi.Output<string>;
```


The name or description of the rule.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/pack/nodejs/waf/rateBasedRule.ts#L33">property predicates</a>
</h3>

```typescript
public predicates: pulumi.Output<{ ... }[] | undefined>;
```


One of ByteMatchSet, IPSet, SizeConstraintSet, SqlInjectionMatchSet, or XssMatchSet objects to include in a rule.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/pack/nodejs/waf/rateBasedRule.ts#L37">property rateKey</a>
</h3>

```typescript
public rateKey: pulumi.Output<string>;
```


Valid value is IP.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/pack/nodejs/waf/rateBasedRule.ts#L41">property rateLimit</a>
</h3>

```typescript
public rateLimit: pulumi.Output<number>;
```


The maximum number of requests, which have an identical value in the field specified by the RateKey, allowed in a five-minute period. Minimum value is 2000.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/pack/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L15">property urn</a>
</h3>

```typescript
urn: Output<URN>;
```


urn is the stable logical URN used to distinctly address a resource, both before and after
deployments.

<h2 class="pdoc-module-header" id="RegexMatchSet">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-aws/blob/master/pack/nodejs/waf/regexMatchSet.ts#L9">class RegexMatchSet</a>
</h2>

Provides a WAF Regex Match Set Resource

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/pack/nodejs/waf/regexMatchSet.ts#L30">constructor</a>
</h3>

```typescript
new RegexMatchSet(name: string, args?: RegexMatchSetArgs, opts?: pulumi.ResourceOptions)
```


Create a RegexMatchSet resource with the given unique name, arguments, and options.

* `name` The _unique_ name of the resource.
* `args` The arguments to use to populate this resource&#39;s properties.
* `opts` A bag of options that control this resource&#39;s behavior.


```typescript
new RegexMatchSet(name: string, state?: RegexMatchSetState, opts?: pulumi.ResourceOptions)
```


Create a RegexMatchSet resource with the given unique name, arguments, and options.

* `name` The _unique_ name of the resource.
* `state` The state to use when looking up an instance of this resource.
* `opts` A bag of options that control this resource&#39;s behavior.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/pack/nodejs/waf/regexMatchSet.ts#L18">method get</a>
</h3>

```typescript
public static get(name: string, id: pulumi.Input<pulumi.ID>, state?: RegexMatchSetState): RegexMatchSet
```


Get an existing RegexMatchSet resource's state with the given name, ID, and optional extra
properties used to qualify the lookup.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/pack/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L72">method isInstance</a>
</h3>

```typescript
static isInstance(obj: any): boolean
```


Returns true if the given object is an instance of CustomResource.  This is designed to work even when
multiple copies of the Pulumi SDK have been loaded into the same process.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/pack/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L67">property id</a>
</h3>

```typescript
id: Output<ID>;
```


id is the provider-assigned unique ID for this managed resource.  It is set during
deployments and may be missing (undefined) during planning phases.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/pack/nodejs/waf/regexMatchSet.ts#L25">property name</a>
</h3>

```typescript
public name: pulumi.Output<string>;
```


The name or description of the Regex Match Set.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/pack/nodejs/waf/regexMatchSet.ts#L30">property regexMatchTuples</a>
</h3>

```typescript
public regexMatchTuples: pulumi.Output<{ ... }[] | undefined>;
```


The regular expression pattern that you want AWS WAF to search for in web requests,
the location in requests that you want AWS WAF to search, and other settings. See below.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/pack/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L15">property urn</a>
</h3>

```typescript
urn: Output<URN>;
```


urn is the stable logical URN used to distinctly address a resource, both before and after
deployments.

<h2 class="pdoc-module-header" id="RegexPatternSet">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-aws/blob/master/pack/nodejs/waf/regexPatternSet.ts#L9">class RegexPatternSet</a>
</h2>

Provides a WAF Regex Pattern Set Resource

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/pack/nodejs/waf/regexPatternSet.ts#L29">constructor</a>
</h3>

```typescript
new RegexPatternSet(name: string, args?: RegexPatternSetArgs, opts?: pulumi.ResourceOptions)
```


Create a RegexPatternSet resource with the given unique name, arguments, and options.

* `name` The _unique_ name of the resource.
* `args` The arguments to use to populate this resource&#39;s properties.
* `opts` A bag of options that control this resource&#39;s behavior.


```typescript
new RegexPatternSet(name: string, state?: RegexPatternSetState, opts?: pulumi.ResourceOptions)
```


Create a RegexPatternSet resource with the given unique name, arguments, and options.

* `name` The _unique_ name of the resource.
* `state` The state to use when looking up an instance of this resource.
* `opts` A bag of options that control this resource&#39;s behavior.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/pack/nodejs/waf/regexPatternSet.ts#L18">method get</a>
</h3>

```typescript
public static get(name: string, id: pulumi.Input<pulumi.ID>, state?: RegexPatternSetState): RegexPatternSet
```


Get an existing RegexPatternSet resource's state with the given name, ID, and optional extra
properties used to qualify the lookup.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/pack/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L72">method isInstance</a>
</h3>

```typescript
static isInstance(obj: any): boolean
```


Returns true if the given object is an instance of CustomResource.  This is designed to work even when
multiple copies of the Pulumi SDK have been loaded into the same process.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/pack/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L67">property id</a>
</h3>

```typescript
id: Output<ID>;
```


id is the provider-assigned unique ID for this managed resource.  It is set during
deployments and may be missing (undefined) during planning phases.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/pack/nodejs/waf/regexPatternSet.ts#L25">property name</a>
</h3>

```typescript
public name: pulumi.Output<string>;
```


The name or description of the Regex Pattern Set.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/pack/nodejs/waf/regexPatternSet.ts#L29">property regexPatternStrings</a>
</h3>

```typescript
public regexPatternStrings: pulumi.Output<string[] | undefined>;
```


A list of regular expression (regex) patterns that you want AWS WAF to search for, such as `B[a@]dB[o0]t`.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/pack/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L15">property urn</a>
</h3>

```typescript
urn: Output<URN>;
```


urn is the stable logical URN used to distinctly address a resource, both before and after
deployments.

<h2 class="pdoc-module-header" id="Rule">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-aws/blob/master/pack/nodejs/waf/rule.ts#L9">class Rule</a>
</h2>

Provides a WAF Rule Resource

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/pack/nodejs/waf/rule.ts#L33">constructor</a>
</h3>

```typescript
new Rule(name: string, args: RuleArgs, opts?: pulumi.ResourceOptions)
```


Create a Rule resource with the given unique name, arguments, and options.

* `name` The _unique_ name of the resource.
* `args` The arguments to use to populate this resource&#39;s properties.
* `opts` A bag of options that control this resource&#39;s behavior.


```typescript
new Rule(name: string, state?: RuleState, opts?: pulumi.ResourceOptions)
```


Create a Rule resource with the given unique name, arguments, and options.

* `name` The _unique_ name of the resource.
* `state` The state to use when looking up an instance of this resource.
* `opts` A bag of options that control this resource&#39;s behavior.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/pack/nodejs/waf/rule.ts#L18">method get</a>
</h3>

```typescript
public static get(name: string, id: pulumi.Input<pulumi.ID>, state?: RuleState): Rule
```


Get an existing Rule resource's state with the given name, ID, and optional extra
properties used to qualify the lookup.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/pack/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L72">method isInstance</a>
</h3>

```typescript
static isInstance(obj: any): boolean
```


Returns true if the given object is an instance of CustomResource.  This is designed to work even when
multiple copies of the Pulumi SDK have been loaded into the same process.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/pack/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L67">property id</a>
</h3>

```typescript
id: Output<ID>;
```


id is the provider-assigned unique ID for this managed resource.  It is set during
deployments and may be missing (undefined) during planning phases.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/pack/nodejs/waf/rule.ts#L25">property metricName</a>
</h3>

```typescript
public metricName: pulumi.Output<string>;
```


The name or description for the Amazon CloudWatch metric of this rule.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/pack/nodejs/waf/rule.ts#L29">property name</a>
</h3>

```typescript
public name: pulumi.Output<string>;
```


The name or description of the rule.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/pack/nodejs/waf/rule.ts#L33">property predicates</a>
</h3>

```typescript
public predicates: pulumi.Output<{ ... }[] | undefined>;
```


One of ByteMatchSet, IPSet, SizeConstraintSet, SqlInjectionMatchSet, or XssMatchSet objects to include in a rule.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/pack/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L15">property urn</a>
</h3>

```typescript
urn: Output<URN>;
```


urn is the stable logical URN used to distinctly address a resource, both before and after
deployments.

<h2 class="pdoc-module-header" id="RuleGroup">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-aws/blob/master/pack/nodejs/waf/ruleGroup.ts#L9">class RuleGroup</a>
</h2>

Provides a WAF Rule Group Resource

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/pack/nodejs/waf/ruleGroup.ts#L33">constructor</a>
</h3>

```typescript
new RuleGroup(name: string, args: RuleGroupArgs, opts?: pulumi.ResourceOptions)
```


Create a RuleGroup resource with the given unique name, arguments, and options.

* `name` The _unique_ name of the resource.
* `args` The arguments to use to populate this resource&#39;s properties.
* `opts` A bag of options that control this resource&#39;s behavior.


```typescript
new RuleGroup(name: string, state?: RuleGroupState, opts?: pulumi.ResourceOptions)
```


Create a RuleGroup resource with the given unique name, arguments, and options.

* `name` The _unique_ name of the resource.
* `state` The state to use when looking up an instance of this resource.
* `opts` A bag of options that control this resource&#39;s behavior.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/pack/nodejs/waf/ruleGroup.ts#L18">method get</a>
</h3>

```typescript
public static get(name: string, id: pulumi.Input<pulumi.ID>, state?: RuleGroupState): RuleGroup
```


Get an existing RuleGroup resource's state with the given name, ID, and optional extra
properties used to qualify the lookup.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/pack/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L72">method isInstance</a>
</h3>

```typescript
static isInstance(obj: any): boolean
```


Returns true if the given object is an instance of CustomResource.  This is designed to work even when
multiple copies of the Pulumi SDK have been loaded into the same process.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/pack/nodejs/waf/ruleGroup.ts#L25">property activatedRules</a>
</h3>

```typescript
public activatedRules: pulumi.Output<{ ... }[] | undefined>;
```


A list of activated rules, see below

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/pack/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L67">property id</a>
</h3>

```typescript
id: Output<ID>;
```


id is the provider-assigned unique ID for this managed resource.  It is set during
deployments and may be missing (undefined) during planning phases.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/pack/nodejs/waf/ruleGroup.ts#L29">property metricName</a>
</h3>

```typescript
public metricName: pulumi.Output<string>;
```


A friendly name for the metrics from the rule group

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/pack/nodejs/waf/ruleGroup.ts#L33">property name</a>
</h3>

```typescript
public name: pulumi.Output<string>;
```


A friendly name of the rule group

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/pack/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L15">property urn</a>
</h3>

```typescript
urn: Output<URN>;
```


urn is the stable logical URN used to distinctly address a resource, both before and after
deployments.

<h2 class="pdoc-module-header" id="SizeConstraintSet">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-aws/blob/master/pack/nodejs/waf/sizeConstraintSet.ts#L9">class SizeConstraintSet</a>
</h2>

Provides a WAF Size Constraint Set Resource

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/pack/nodejs/waf/sizeConstraintSet.ts#L29">constructor</a>
</h3>

```typescript
new SizeConstraintSet(name: string, args?: SizeConstraintSetArgs, opts?: pulumi.ResourceOptions)
```


Create a SizeConstraintSet resource with the given unique name, arguments, and options.

* `name` The _unique_ name of the resource.
* `args` The arguments to use to populate this resource&#39;s properties.
* `opts` A bag of options that control this resource&#39;s behavior.


```typescript
new SizeConstraintSet(name: string, state?: SizeConstraintSetState, opts?: pulumi.ResourceOptions)
```


Create a SizeConstraintSet resource with the given unique name, arguments, and options.

* `name` The _unique_ name of the resource.
* `state` The state to use when looking up an instance of this resource.
* `opts` A bag of options that control this resource&#39;s behavior.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/pack/nodejs/waf/sizeConstraintSet.ts#L18">method get</a>
</h3>

```typescript
public static get(name: string, id: pulumi.Input<pulumi.ID>, state?: SizeConstraintSetState): SizeConstraintSet
```


Get an existing SizeConstraintSet resource's state with the given name, ID, and optional extra
properties used to qualify the lookup.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/pack/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L72">method isInstance</a>
</h3>

```typescript
static isInstance(obj: any): boolean
```


Returns true if the given object is an instance of CustomResource.  This is designed to work even when
multiple copies of the Pulumi SDK have been loaded into the same process.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/pack/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L67">property id</a>
</h3>

```typescript
id: Output<ID>;
```


id is the provider-assigned unique ID for this managed resource.  It is set during
deployments and may be missing (undefined) during planning phases.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/pack/nodejs/waf/sizeConstraintSet.ts#L25">property name</a>
</h3>

```typescript
public name: pulumi.Output<string>;
```


The name or description of the Size Constraint Set.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/pack/nodejs/waf/sizeConstraintSet.ts#L29">property sizeConstraints</a>
</h3>

```typescript
public sizeConstraints: pulumi.Output<{ ... }[] | undefined>;
```


Specifies the parts of web requests that you want to inspect the size of.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/pack/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L15">property urn</a>
</h3>

```typescript
urn: Output<URN>;
```


urn is the stable logical URN used to distinctly address a resource, both before and after
deployments.

<h2 class="pdoc-module-header" id="SqlInjectionMatchSet">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-aws/blob/master/pack/nodejs/waf/sqlInjectionMatchSet.ts#L9">class SqlInjectionMatchSet</a>
</h2>

Provides a WAF SQL Injection Match Set Resource

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/pack/nodejs/waf/sqlInjectionMatchSet.ts#L29">constructor</a>
</h3>

```typescript
new SqlInjectionMatchSet(name: string, args?: SqlInjectionMatchSetArgs, opts?: pulumi.ResourceOptions)
```


Create a SqlInjectionMatchSet resource with the given unique name, arguments, and options.

* `name` The _unique_ name of the resource.
* `args` The arguments to use to populate this resource&#39;s properties.
* `opts` A bag of options that control this resource&#39;s behavior.


```typescript
new SqlInjectionMatchSet(name: string, state?: SqlInjectionMatchSetState, opts?: pulumi.ResourceOptions)
```


Create a SqlInjectionMatchSet resource with the given unique name, arguments, and options.

* `name` The _unique_ name of the resource.
* `state` The state to use when looking up an instance of this resource.
* `opts` A bag of options that control this resource&#39;s behavior.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/pack/nodejs/waf/sqlInjectionMatchSet.ts#L18">method get</a>
</h3>

```typescript
public static get(name: string, id: pulumi.Input<pulumi.ID>, state?: SqlInjectionMatchSetState): SqlInjectionMatchSet
```


Get an existing SqlInjectionMatchSet resource's state with the given name, ID, and optional extra
properties used to qualify the lookup.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/pack/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L72">method isInstance</a>
</h3>

```typescript
static isInstance(obj: any): boolean
```


Returns true if the given object is an instance of CustomResource.  This is designed to work even when
multiple copies of the Pulumi SDK have been loaded into the same process.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/pack/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L67">property id</a>
</h3>

```typescript
id: Output<ID>;
```


id is the provider-assigned unique ID for this managed resource.  It is set during
deployments and may be missing (undefined) during planning phases.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/pack/nodejs/waf/sqlInjectionMatchSet.ts#L25">property name</a>
</h3>

```typescript
public name: pulumi.Output<string>;
```


The name or description of the SizeConstraintSet.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/pack/nodejs/waf/sqlInjectionMatchSet.ts#L29">property sqlInjectionMatchTuples</a>
</h3>

```typescript
public sqlInjectionMatchTuples: pulumi.Output<{ ... }[] | undefined>;
```


The parts of web requests that you want AWS WAF to inspect for malicious SQL code and, if you want AWS WAF to inspect a header, the name of the header.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/pack/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L15">property urn</a>
</h3>

```typescript
urn: Output<URN>;
```


urn is the stable logical URN used to distinctly address a resource, both before and after
deployments.

<h2 class="pdoc-module-header" id="WebAcl">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-aws/blob/master/pack/nodejs/waf/webAcl.ts#L9">class WebAcl</a>
</h2>

Provides a WAF Web ACL Resource

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/pack/nodejs/waf/webAcl.ts#L37">constructor</a>
</h3>

```typescript
new WebAcl(name: string, args: WebAclArgs, opts?: pulumi.ResourceOptions)
```


Create a WebAcl resource with the given unique name, arguments, and options.

* `name` The _unique_ name of the resource.
* `args` The arguments to use to populate this resource&#39;s properties.
* `opts` A bag of options that control this resource&#39;s behavior.


```typescript
new WebAcl(name: string, state?: WebAclState, opts?: pulumi.ResourceOptions)
```


Create a WebAcl resource with the given unique name, arguments, and options.

* `name` The _unique_ name of the resource.
* `state` The state to use when looking up an instance of this resource.
* `opts` A bag of options that control this resource&#39;s behavior.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/pack/nodejs/waf/webAcl.ts#L18">method get</a>
</h3>

```typescript
public static get(name: string, id: pulumi.Input<pulumi.ID>, state?: WebAclState): WebAcl
```


Get an existing WebAcl resource's state with the given name, ID, and optional extra
properties used to qualify the lookup.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/pack/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L72">method isInstance</a>
</h3>

```typescript
static isInstance(obj: any): boolean
```


Returns true if the given object is an instance of CustomResource.  This is designed to work even when
multiple copies of the Pulumi SDK have been loaded into the same process.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/pack/nodejs/waf/webAcl.ts#L25">property defaultAction</a>
</h3>

```typescript
public defaultAction: pulumi.Output<{ ... }>;
```


The action that you want AWS WAF to take when a request doesn't match the criteria in any of the rules that are associated with the web ACL.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/pack/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L67">property id</a>
</h3>

```typescript
id: Output<ID>;
```


id is the provider-assigned unique ID for this managed resource.  It is set during
deployments and may be missing (undefined) during planning phases.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/pack/nodejs/waf/webAcl.ts#L29">property metricName</a>
</h3>

```typescript
public metricName: pulumi.Output<string>;
```


The name or description for the Amazon CloudWatch metric of this web ACL.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/pack/nodejs/waf/webAcl.ts#L33">property name</a>
</h3>

```typescript
public name: pulumi.Output<string>;
```


The name or description of the web ACL.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/pack/nodejs/waf/webAcl.ts#L37">property rules</a>
</h3>

```typescript
public rules: pulumi.Output<{ ... }[] | undefined>;
```


The rules to associate with the web ACL and the settings for each rule.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/pack/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L15">property urn</a>
</h3>

```typescript
urn: Output<URN>;
```


urn is the stable logical URN used to distinctly address a resource, both before and after
deployments.

<h2 class="pdoc-module-header" id="XssMatchSet">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-aws/blob/master/pack/nodejs/waf/xssMatchSet.ts#L9">class XssMatchSet</a>
</h2>

Provides a WAF XSS Match Set Resource

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/pack/nodejs/waf/xssMatchSet.ts#L29">constructor</a>
</h3>

```typescript
new XssMatchSet(name: string, args?: XssMatchSetArgs, opts?: pulumi.ResourceOptions)
```


Create a XssMatchSet resource with the given unique name, arguments, and options.

* `name` The _unique_ name of the resource.
* `args` The arguments to use to populate this resource&#39;s properties.
* `opts` A bag of options that control this resource&#39;s behavior.


```typescript
new XssMatchSet(name: string, state?: XssMatchSetState, opts?: pulumi.ResourceOptions)
```


Create a XssMatchSet resource with the given unique name, arguments, and options.

* `name` The _unique_ name of the resource.
* `state` The state to use when looking up an instance of this resource.
* `opts` A bag of options that control this resource&#39;s behavior.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/pack/nodejs/waf/xssMatchSet.ts#L18">method get</a>
</h3>

```typescript
public static get(name: string, id: pulumi.Input<pulumi.ID>, state?: XssMatchSetState): XssMatchSet
```


Get an existing XssMatchSet resource's state with the given name, ID, and optional extra
properties used to qualify the lookup.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/pack/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L72">method isInstance</a>
</h3>

```typescript
static isInstance(obj: any): boolean
```


Returns true if the given object is an instance of CustomResource.  This is designed to work even when
multiple copies of the Pulumi SDK have been loaded into the same process.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/pack/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L67">property id</a>
</h3>

```typescript
id: Output<ID>;
```


id is the provider-assigned unique ID for this managed resource.  It is set during
deployments and may be missing (undefined) during planning phases.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/pack/nodejs/waf/xssMatchSet.ts#L25">property name</a>
</h3>

```typescript
public name: pulumi.Output<string>;
```


The name or description of the SizeConstraintSet.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/pack/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L15">property urn</a>
</h3>

```typescript
urn: Output<URN>;
```


urn is the stable logical URN used to distinctly address a resource, both before and after
deployments.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/pack/nodejs/waf/xssMatchSet.ts#L29">property xssMatchTuples</a>
</h3>

```typescript
public xssMatchTuples: pulumi.Output<{ ... }[] | undefined>;
```


The parts of web requests that you want to inspect for cross-site scripting attacks.

<h2 class="pdoc-module-header" id="ByteMatchSetArgs">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-aws/blob/master/pack/nodejs/waf/byteMatchSet.ts#L77">interface ByteMatchSetArgs</a>
</h2>

The set of arguments for constructing a ByteMatchSet resource.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/pack/nodejs/waf/byteMatchSet.ts#L83">property byteMatchTuples</a>
</h3>

```typescript
byteMatchTuples?: pulumi.Input<{ ... }[]>;
```


Specifies the bytes (typically a string that corresponds
with ASCII characters) that you want to search for in web requests,
the location in requests that you want to search, and other settings.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/pack/nodejs/waf/byteMatchSet.ts#L87">property name</a>
</h3>

```typescript
name?: pulumi.Input<string>;
```


The name or description of the Byte Match Set.

<h2 class="pdoc-module-header" id="ByteMatchSetState">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-aws/blob/master/pack/nodejs/waf/byteMatchSet.ts#L61">interface ByteMatchSetState</a>
</h2>

Input properties used for looking up and filtering ByteMatchSet resources.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/pack/nodejs/waf/byteMatchSet.ts#L67">property byteMatchTuples</a>
</h3>

```typescript
byteMatchTuples?: pulumi.Input<{ ... }[]>;
```


Specifies the bytes (typically a string that corresponds
with ASCII characters) that you want to search for in web requests,
the location in requests that you want to search, and other settings.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/pack/nodejs/waf/byteMatchSet.ts#L71">property name</a>
</h3>

```typescript
name?: pulumi.Input<string>;
```


The name or description of the Byte Match Set.

<h2 class="pdoc-module-header" id="GeoMatchSetArgs">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-aws/blob/master/pack/nodejs/waf/geoMatchSet.ts#L73">interface GeoMatchSetArgs</a>
</h2>

The set of arguments for constructing a GeoMatchSet resource.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/pack/nodejs/waf/geoMatchSet.ts#L77">property geoMatchConstraints</a>
</h3>

```typescript
geoMatchConstraints?: pulumi.Input<{ ... }[]>;
```


The GeoMatchConstraint objects which contain the country that you want AWS WAF to search for.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/pack/nodejs/waf/geoMatchSet.ts#L81">property name</a>
</h3>

```typescript
name?: pulumi.Input<string>;
```


The name or description of the GeoMatchSet.

<h2 class="pdoc-module-header" id="GeoMatchSetState">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-aws/blob/master/pack/nodejs/waf/geoMatchSet.ts#L59">interface GeoMatchSetState</a>
</h2>

Input properties used for looking up and filtering GeoMatchSet resources.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/pack/nodejs/waf/geoMatchSet.ts#L63">property geoMatchConstraints</a>
</h3>

```typescript
geoMatchConstraints?: pulumi.Input<{ ... }[]>;
```


The GeoMatchConstraint objects which contain the country that you want AWS WAF to search for.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/pack/nodejs/waf/geoMatchSet.ts#L67">property name</a>
</h3>

```typescript
name?: pulumi.Input<string>;
```


The name or description of the GeoMatchSet.

<h2 class="pdoc-module-header" id="IpSetArgs">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-aws/blob/master/pack/nodejs/waf/ipSet.ts#L75">interface IpSetArgs</a>
</h2>

The set of arguments for constructing a IpSet resource.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/pack/nodejs/waf/ipSet.ts#L80">property ipSetDescriptors</a>
</h3>

```typescript
ipSetDescriptors?: pulumi.Input<{ ... }[]>;
```


Specifies the IP address type (IPV4 or IPV6)
and the IP address range (in CIDR format) that web requests originate from.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/pack/nodejs/waf/ipSet.ts#L84">property name</a>
</h3>

```typescript
name?: pulumi.Input<string>;
```


The name or description of the IPSet.

<h2 class="pdoc-module-header" id="IpSetState">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-aws/blob/master/pack/nodejs/waf/ipSet.ts#L60">interface IpSetState</a>
</h2>

Input properties used for looking up and filtering IpSet resources.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/pack/nodejs/waf/ipSet.ts#L65">property ipSetDescriptors</a>
</h3>

```typescript
ipSetDescriptors?: pulumi.Input<{ ... }[]>;
```


Specifies the IP address type (IPV4 or IPV6)
and the IP address range (in CIDR format) that web requests originate from.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/pack/nodejs/waf/ipSet.ts#L69">property name</a>
</h3>

```typescript
name?: pulumi.Input<string>;
```


The name or description of the IPSet.

<h2 class="pdoc-module-header" id="RateBasedRuleArgs">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-aws/blob/master/pack/nodejs/waf/rateBasedRule.ts#L112">interface RateBasedRuleArgs</a>
</h2>

The set of arguments for constructing a RateBasedRule resource.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/pack/nodejs/waf/rateBasedRule.ts#L116">property metricName</a>
</h3>

```typescript
metricName: pulumi.Input<string>;
```


The name or description for the Amazon CloudWatch metric of this rule.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/pack/nodejs/waf/rateBasedRule.ts#L120">property name</a>
</h3>

```typescript
name?: pulumi.Input<string>;
```


The name or description of the rule.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/pack/nodejs/waf/rateBasedRule.ts#L124">property predicates</a>
</h3>

```typescript
predicates?: pulumi.Input<{ ... }[]>;
```


One of ByteMatchSet, IPSet, SizeConstraintSet, SqlInjectionMatchSet, or XssMatchSet objects to include in a rule.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/pack/nodejs/waf/rateBasedRule.ts#L128">property rateKey</a>
</h3>

```typescript
rateKey: pulumi.Input<string>;
```


Valid value is IP.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/pack/nodejs/waf/rateBasedRule.ts#L132">property rateLimit</a>
</h3>

```typescript
rateLimit: pulumi.Input<number>;
```


The maximum number of requests, which have an identical value in the field specified by the RateKey, allowed in a five-minute period. Minimum value is 2000.

<h2 class="pdoc-module-header" id="RateBasedRuleState">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-aws/blob/master/pack/nodejs/waf/rateBasedRule.ts#L86">interface RateBasedRuleState</a>
</h2>

Input properties used for looking up and filtering RateBasedRule resources.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/pack/nodejs/waf/rateBasedRule.ts#L90">property metricName</a>
</h3>

```typescript
metricName?: pulumi.Input<string>;
```


The name or description for the Amazon CloudWatch metric of this rule.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/pack/nodejs/waf/rateBasedRule.ts#L94">property name</a>
</h3>

```typescript
name?: pulumi.Input<string>;
```


The name or description of the rule.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/pack/nodejs/waf/rateBasedRule.ts#L98">property predicates</a>
</h3>

```typescript
predicates?: pulumi.Input<{ ... }[]>;
```


One of ByteMatchSet, IPSet, SizeConstraintSet, SqlInjectionMatchSet, or XssMatchSet objects to include in a rule.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/pack/nodejs/waf/rateBasedRule.ts#L102">property rateKey</a>
</h3>

```typescript
rateKey?: pulumi.Input<string>;
```


Valid value is IP.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/pack/nodejs/waf/rateBasedRule.ts#L106">property rateLimit</a>
</h3>

```typescript
rateLimit?: pulumi.Input<number>;
```


The maximum number of requests, which have an identical value in the field specified by the RateKey, allowed in a five-minute period. Minimum value is 2000.

<h2 class="pdoc-module-header" id="RegexMatchSetArgs">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-aws/blob/master/pack/nodejs/waf/regexMatchSet.ts#L75">interface RegexMatchSetArgs</a>
</h2>

The set of arguments for constructing a RegexMatchSet resource.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/pack/nodejs/waf/regexMatchSet.ts#L79">property name</a>
</h3>

```typescript
name?: pulumi.Input<string>;
```


The name or description of the Regex Match Set.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/pack/nodejs/waf/regexMatchSet.ts#L84">property regexMatchTuples</a>
</h3>

```typescript
regexMatchTuples?: pulumi.Input<{ ... }[]>;
```


The regular expression pattern that you want AWS WAF to search for in web requests,
the location in requests that you want AWS WAF to search, and other settings. See below.

<h2 class="pdoc-module-header" id="RegexMatchSetState">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-aws/blob/master/pack/nodejs/waf/regexMatchSet.ts#L60">interface RegexMatchSetState</a>
</h2>

Input properties used for looking up and filtering RegexMatchSet resources.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/pack/nodejs/waf/regexMatchSet.ts#L64">property name</a>
</h3>

```typescript
name?: pulumi.Input<string>;
```


The name or description of the Regex Match Set.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/pack/nodejs/waf/regexMatchSet.ts#L69">property regexMatchTuples</a>
</h3>

```typescript
regexMatchTuples?: pulumi.Input<{ ... }[]>;
```


The regular expression pattern that you want AWS WAF to search for in web requests,
the location in requests that you want AWS WAF to search, and other settings. See below.

<h2 class="pdoc-module-header" id="RegexPatternSetArgs">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-aws/blob/master/pack/nodejs/waf/regexPatternSet.ts#L73">interface RegexPatternSetArgs</a>
</h2>

The set of arguments for constructing a RegexPatternSet resource.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/pack/nodejs/waf/regexPatternSet.ts#L77">property name</a>
</h3>

```typescript
name?: pulumi.Input<string>;
```


The name or description of the Regex Pattern Set.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/pack/nodejs/waf/regexPatternSet.ts#L81">property regexPatternStrings</a>
</h3>

```typescript
regexPatternStrings?: pulumi.Input<pulumi.Input<string>[]>;
```


A list of regular expression (regex) patterns that you want AWS WAF to search for, such as `B[a@]dB[o0]t`.

<h2 class="pdoc-module-header" id="RegexPatternSetState">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-aws/blob/master/pack/nodejs/waf/regexPatternSet.ts#L59">interface RegexPatternSetState</a>
</h2>

Input properties used for looking up and filtering RegexPatternSet resources.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/pack/nodejs/waf/regexPatternSet.ts#L63">property name</a>
</h3>

```typescript
name?: pulumi.Input<string>;
```


The name or description of the Regex Pattern Set.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/pack/nodejs/waf/regexPatternSet.ts#L67">property regexPatternStrings</a>
</h3>

```typescript
regexPatternStrings?: pulumi.Input<pulumi.Input<string>[]>;
```


A list of regular expression (regex) patterns that you want AWS WAF to search for, such as `B[a@]dB[o0]t`.

<h2 class="pdoc-module-header" id="RuleArgs">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-aws/blob/master/pack/nodejs/waf/rule.ts#L86">interface RuleArgs</a>
</h2>

The set of arguments for constructing a Rule resource.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/pack/nodejs/waf/rule.ts#L90">property metricName</a>
</h3>

```typescript
metricName: pulumi.Input<string>;
```


The name or description for the Amazon CloudWatch metric of this rule.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/pack/nodejs/waf/rule.ts#L94">property name</a>
</h3>

```typescript
name?: pulumi.Input<string>;
```


The name or description of the rule.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/pack/nodejs/waf/rule.ts#L98">property predicates</a>
</h3>

```typescript
predicates?: pulumi.Input<{ ... }[]>;
```


One of ByteMatchSet, IPSet, SizeConstraintSet, SqlInjectionMatchSet, or XssMatchSet objects to include in a rule.

<h2 class="pdoc-module-header" id="RuleGroupArgs">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-aws/blob/master/pack/nodejs/waf/ruleGroup.ts#L86">interface RuleGroupArgs</a>
</h2>

The set of arguments for constructing a RuleGroup resource.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/pack/nodejs/waf/ruleGroup.ts#L90">property activatedRules</a>
</h3>

```typescript
activatedRules?: pulumi.Input<{ ... }[]>;
```


A list of activated rules, see below

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/pack/nodejs/waf/ruleGroup.ts#L94">property metricName</a>
</h3>

```typescript
metricName: pulumi.Input<string>;
```


A friendly name for the metrics from the rule group

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/pack/nodejs/waf/ruleGroup.ts#L98">property name</a>
</h3>

```typescript
name?: pulumi.Input<string>;
```


A friendly name of the rule group

<h2 class="pdoc-module-header" id="RuleGroupState">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-aws/blob/master/pack/nodejs/waf/ruleGroup.ts#L68">interface RuleGroupState</a>
</h2>

Input properties used for looking up and filtering RuleGroup resources.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/pack/nodejs/waf/ruleGroup.ts#L72">property activatedRules</a>
</h3>

```typescript
activatedRules?: pulumi.Input<{ ... }[]>;
```


A list of activated rules, see below

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/pack/nodejs/waf/ruleGroup.ts#L76">property metricName</a>
</h3>

```typescript
metricName?: pulumi.Input<string>;
```


A friendly name for the metrics from the rule group

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/pack/nodejs/waf/ruleGroup.ts#L80">property name</a>
</h3>

```typescript
name?: pulumi.Input<string>;
```


A friendly name of the rule group

<h2 class="pdoc-module-header" id="RuleState">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-aws/blob/master/pack/nodejs/waf/rule.ts#L68">interface RuleState</a>
</h2>

Input properties used for looking up and filtering Rule resources.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/pack/nodejs/waf/rule.ts#L72">property metricName</a>
</h3>

```typescript
metricName?: pulumi.Input<string>;
```


The name or description for the Amazon CloudWatch metric of this rule.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/pack/nodejs/waf/rule.ts#L76">property name</a>
</h3>

```typescript
name?: pulumi.Input<string>;
```


The name or description of the rule.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/pack/nodejs/waf/rule.ts#L80">property predicates</a>
</h3>

```typescript
predicates?: pulumi.Input<{ ... }[]>;
```


One of ByteMatchSet, IPSet, SizeConstraintSet, SqlInjectionMatchSet, or XssMatchSet objects to include in a rule.

<h2 class="pdoc-module-header" id="SizeConstraintSetArgs">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-aws/blob/master/pack/nodejs/waf/sizeConstraintSet.ts#L73">interface SizeConstraintSetArgs</a>
</h2>

The set of arguments for constructing a SizeConstraintSet resource.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/pack/nodejs/waf/sizeConstraintSet.ts#L77">property name</a>
</h3>

```typescript
name?: pulumi.Input<string>;
```


The name or description of the Size Constraint Set.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/pack/nodejs/waf/sizeConstraintSet.ts#L81">property sizeConstraints</a>
</h3>

```typescript
sizeConstraints?: pulumi.Input<{ ... }[]>;
```


Specifies the parts of web requests that you want to inspect the size of.

<h2 class="pdoc-module-header" id="SizeConstraintSetState">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-aws/blob/master/pack/nodejs/waf/sizeConstraintSet.ts#L59">interface SizeConstraintSetState</a>
</h2>

Input properties used for looking up and filtering SizeConstraintSet resources.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/pack/nodejs/waf/sizeConstraintSet.ts#L63">property name</a>
</h3>

```typescript
name?: pulumi.Input<string>;
```


The name or description of the Size Constraint Set.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/pack/nodejs/waf/sizeConstraintSet.ts#L67">property sizeConstraints</a>
</h3>

```typescript
sizeConstraints?: pulumi.Input<{ ... }[]>;
```


Specifies the parts of web requests that you want to inspect the size of.

<h2 class="pdoc-module-header" id="SqlInjectionMatchSetArgs">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-aws/blob/master/pack/nodejs/waf/sqlInjectionMatchSet.ts#L73">interface SqlInjectionMatchSetArgs</a>
</h2>

The set of arguments for constructing a SqlInjectionMatchSet resource.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/pack/nodejs/waf/sqlInjectionMatchSet.ts#L77">property name</a>
</h3>

```typescript
name?: pulumi.Input<string>;
```


The name or description of the SizeConstraintSet.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/pack/nodejs/waf/sqlInjectionMatchSet.ts#L81">property sqlInjectionMatchTuples</a>
</h3>

```typescript
sqlInjectionMatchTuples?: pulumi.Input<{ ... }[]>;
```


The parts of web requests that you want AWS WAF to inspect for malicious SQL code and, if you want AWS WAF to inspect a header, the name of the header.

<h2 class="pdoc-module-header" id="SqlInjectionMatchSetState">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-aws/blob/master/pack/nodejs/waf/sqlInjectionMatchSet.ts#L59">interface SqlInjectionMatchSetState</a>
</h2>

Input properties used for looking up and filtering SqlInjectionMatchSet resources.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/pack/nodejs/waf/sqlInjectionMatchSet.ts#L63">property name</a>
</h3>

```typescript
name?: pulumi.Input<string>;
```


The name or description of the SizeConstraintSet.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/pack/nodejs/waf/sqlInjectionMatchSet.ts#L67">property sqlInjectionMatchTuples</a>
</h3>

```typescript
sqlInjectionMatchTuples?: pulumi.Input<{ ... }[]>;
```


The parts of web requests that you want AWS WAF to inspect for malicious SQL code and, if you want AWS WAF to inspect a header, the name of the header.

<h2 class="pdoc-module-header" id="WebAclArgs">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-aws/blob/master/pack/nodejs/waf/webAcl.ts#L99">interface WebAclArgs</a>
</h2>

The set of arguments for constructing a WebAcl resource.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/pack/nodejs/waf/webAcl.ts#L103">property defaultAction</a>
</h3>

```typescript
defaultAction: pulumi.Input<{ ... }>;
```


The action that you want AWS WAF to take when a request doesn't match the criteria in any of the rules that are associated with the web ACL.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/pack/nodejs/waf/webAcl.ts#L107">property metricName</a>
</h3>

```typescript
metricName: pulumi.Input<string>;
```


The name or description for the Amazon CloudWatch metric of this web ACL.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/pack/nodejs/waf/webAcl.ts#L111">property name</a>
</h3>

```typescript
name?: pulumi.Input<string>;
```


The name or description of the web ACL.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/pack/nodejs/waf/webAcl.ts#L115">property rules</a>
</h3>

```typescript
rules?: pulumi.Input<{ ... }[]>;
```


The rules to associate with the web ACL and the settings for each rule.

<h2 class="pdoc-module-header" id="WebAclState">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-aws/blob/master/pack/nodejs/waf/webAcl.ts#L77">interface WebAclState</a>
</h2>

Input properties used for looking up and filtering WebAcl resources.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/pack/nodejs/waf/webAcl.ts#L81">property defaultAction</a>
</h3>

```typescript
defaultAction?: pulumi.Input<{ ... }>;
```


The action that you want AWS WAF to take when a request doesn't match the criteria in any of the rules that are associated with the web ACL.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/pack/nodejs/waf/webAcl.ts#L85">property metricName</a>
</h3>

```typescript
metricName?: pulumi.Input<string>;
```


The name or description for the Amazon CloudWatch metric of this web ACL.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/pack/nodejs/waf/webAcl.ts#L89">property name</a>
</h3>

```typescript
name?: pulumi.Input<string>;
```


The name or description of the web ACL.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/pack/nodejs/waf/webAcl.ts#L93">property rules</a>
</h3>

```typescript
rules?: pulumi.Input<{ ... }[]>;
```


The rules to associate with the web ACL and the settings for each rule.

<h2 class="pdoc-module-header" id="XssMatchSetArgs">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-aws/blob/master/pack/nodejs/waf/xssMatchSet.ts#L73">interface XssMatchSetArgs</a>
</h2>

The set of arguments for constructing a XssMatchSet resource.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/pack/nodejs/waf/xssMatchSet.ts#L77">property name</a>
</h3>

```typescript
name?: pulumi.Input<string>;
```


The name or description of the SizeConstraintSet.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/pack/nodejs/waf/xssMatchSet.ts#L81">property xssMatchTuples</a>
</h3>

```typescript
xssMatchTuples?: pulumi.Input<{ ... }[]>;
```


The parts of web requests that you want to inspect for cross-site scripting attacks.

<h2 class="pdoc-module-header" id="XssMatchSetState">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-aws/blob/master/pack/nodejs/waf/xssMatchSet.ts#L59">interface XssMatchSetState</a>
</h2>

Input properties used for looking up and filtering XssMatchSet resources.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/pack/nodejs/waf/xssMatchSet.ts#L63">property name</a>
</h3>

```typescript
name?: pulumi.Input<string>;
```


The name or description of the SizeConstraintSet.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/pack/nodejs/waf/xssMatchSet.ts#L67">property xssMatchTuples</a>
</h3>

```typescript
xssMatchTuples?: pulumi.Input<{ ... }[]>;
```


The parts of web requests that you want to inspect for cross-site scripting attacks.
