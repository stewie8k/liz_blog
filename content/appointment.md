---
title: "在线预约"
date: 2024-03-19
layout: "appointment"
---

# 在线预约

欢迎预约宝烨珠宝的专属服务，我们将为您提供专业的珠宝咨询和定制服务。

## 预约服务类型

- 珠宝定制咨询
- 产品试戴体验
- 珠宝保养服务
- 专业鉴定服务

## 预约流程

1. 填写预约信息
2. 选择服务类型和时间
3. 提交预约申请
4. 客服确认预约
5. 按时到店体验

## 预约表单

<div class="appointment-form">
  <form name="appointment" method="POST" data-netlify="true">
    <input type="hidden" name="form-name" value="appointment" />
    
    <div class="form-group">
      <label for="name">姓名</label>
      <input type="text" id="name" name="name" required />
    </div>

    <div class="form-group">
      <label for="phone">联系电话</label>
      <input type="tel" id="phone" name="phone" required />
    </div>

    <div class="form-group">
      <label for="email">电子邮箱</label>
      <input type="email" id="email" name="email" required />
    </div>

    <div class="form-group">
      <label for="service">服务类型</label>
      <select id="service" name="service" required>
        <option value="">请选择服务类型</option>
        <option value="custom">珠宝定制咨询</option>
        <option value="try">产品试戴体验</option>
        <option value="care">珠宝保养服务</option>
        <option value="appraisal">专业鉴定服务</option>
      </select>
    </div>

    <div class="form-group">
      <label for="date">预约日期</label>
      <input type="date" id="date" name="date" required />
    </div>

    <div class="form-group">
      <label for="time">预约时间</label>
      <select id="time" name="time" required>
        <option value="">请选择时间</option>
        <option value="10:00">10:00</option>
        <option value="11:00">11:00</option>
        <option value="14:00">14:00</option>
        <option value="15:00">15:00</option>
        <option value="16:00">16:00</option>
      </select>
    </div>

    <div class="form-group">
      <label for="message">备注信息</label>
      <textarea id="message" name="message" rows="4"></textarea>
    </div>

    <button type="submit">提交预约</button>
  </form>
</div> 