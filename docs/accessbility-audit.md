# Accessibility Audit Report

## Website Audited

**Website:** Karnataka Government Website  
**URL:** https://karnataka.gov.in/english

## Audit Method

The website was evaluated using Google Lighthouse and a manual keyboard-only navigation check.

### Lighthouse Results

- Performance: 40
- Accessibility: 75
- Best Practices: 88
- SEO: 67

## Accessibility Findings

### 1. Buttons do not have an accessible name

**Evidence: Lighthouse identified buttons that do not have an accessible name.

**Priority:** High

**Remediation:** Provide a clear accessible name using meaningful visible text or an appropriate accessible label.

**Ownership:** Frontend Development Team

---

### 2. Image elements do not have alt attributes

**Evidence:** Lighthouse identified image elements without `alt` attributes.

**Priority:** High

**Remediation:** Add meaningful alternative text to informative images and appropriate empty `alt` attributes to decorative images.

**Ownership:** Frontend Development Team

---

### 3. Links do not have a discernible name

**Evidence:** Lighthouse identified links that do not have a discernible accessible name.

**Priority:** High

**Remediation:** Give meaningful links an accessible name that clearly describes their destination or action.

**Ownership:** Frontend Development Team

---

### 4. Background and foreground colors do not have sufficient contrast

**Evidence:** Lighthouse reported insufficient contrast between background and foreground colors.

**Priority:** Medium

**Remediation:** Adjust the foreground and background colors to provide sufficient contrast and improve readability.

**Ownership:** UI/Frontend Development Team

---

### 5. Heading elements are not in a sequentially-descending order

**Evidence:** Lighthouse identified an incorrect heading order and showed a failing `h5` element.

**Priority:** Medium

**Remediation:** Organize headings in a logical hierarchical order so that the page structure is easier to understand with assistive technologies.

**Ownership:** Frontend/Content Team

## Keyboard-Only Navigation

A manual keyboard-only navigation check was performed using Tab, Shift+Tab, and Enter.

**Observation:** No obvious keyboard navigation issue was observed during the manual check.

## Summary

The Lighthouse accessibility audit produced an accessibility score of 75 and identified several opportunities to improve accessibility, semantic structure, readability, and the experience for users of assistive technologies.
