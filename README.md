# 🚀 Project 1: AWS Multi-AZ VPC Architecture

**Engineer:** Mayank Kemani | **From:** Data Center L1 → Cloud Engineer
**Region:** Asia Pacific (Mumbai) ap-south-1
**Cost:** $0.00 - Built on AWS Free Tier
**Status:** ✅ VPC Layer Complete | **Date:** 14-05-2026

## 📌 Project Overview
Designed and deployed a production-grade, highly available Virtual Private Cloud (VPC) from scratch to replicate traditional enterprise Data Center network architecture on AWS Cloud.

This is Project #1 of my "Data Center to Cloud" migration journey.

## 🔧 Technical Implementation
1. **Custom VPC:** 10.0.0.0/16 CIDR - Provides 65,536 Private IPs
2. **High Availability:** Deployed across 2 Availability Zones (ap-south-1a, 1b) for 99.99% uptime
3. **Network Segmentation:**
   - 2x Public Subnets /20 for Web Tier (DMZ) - Internet Gateway Routed
   - 2x Private Subnets /20 for Database Tier - Fully Isolated
4. **Security:** Layered security with Subnets, Route Tables, and NACLs
5. **Cost Optimization:** Zero monthly cost using Free Tier resources

## 💡 Key AWS Services Used
`Amazon VPC` `Subnets` `Route Tables` `Internet Gateway` `Availability Zones`

## 🎯 Skills Demonstrated
Cloud Networking, High Availability Design, Security Best Practices, AWS Free Tier Management, Data Center to Cloud Migration

## 📈 Project Roadmap
- [x] Phase 1: VPC Foundation ✅
- [ ] Phase 2: Deploy EC2 Web Server in Public Subnet
- [ ] Phase 3: Configure Application Load Balancer
- [ ] Phase 4: Setup Auto Scaling Group

---
**Note:** All resources built under AWS Free Tier to ensure zero billing. Perfect for learning & portfolio building.
