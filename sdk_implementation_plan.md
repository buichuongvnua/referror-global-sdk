# Referror Global SDK Implementation Plan

## Overview
Implement Referror Global SDK features as SDK with 3 components:
1. Backend SDK (BE)
2. Web SDK
3. Mobile SDK

## SDK Architecture

### 1. Backend SDK
- Core business logic processing
- Provides APIs for Web and Mobile SDK
- Main modules:
  - Workspace: Multi-workspace management, role-based access control, workspace settings
  - Users: User management, permissions, team collaboration, activity tracking
  - Contacts: Contact management with custom fields (text, number, date, time, dropdown, checkbox, email, URL)
  - Conversations: Unified inbox for all messaging channels (WhatsApp, TikTok, Facebook, Instagram, Telegram, Viber, LINE, WeChat, SMS, Email, Live Chat)
  - Dashboard: Statistics, metrics, customizable widgets
  - Broadcasts: Mass messaging, scheduling, analytics
  - Workflows: Automation rules, conditional workflows, templates
  - Reports: Conversation metrics, team performance, custom reports
  - Files: Storage for messages, broadcasts and workflows with file management

### 2. Web SDK
- Web user interface
- Easy JavaScript integration
- Main modules:
  - Chat widget with multi-channel support (WhatsApp, TikTok, Facebook, Instagram, Telegram, Viber, LINE, WeChat, SMS, Email, Live Chat)
  - Admin dashboard with real-time analytics and customizable widgets
  - Contact management UI with custom fields (text, number, date, time, dropdown, checkbox, email, URL)
  - Conversation history with search and filtering capabilities
  - Team collaboration features with role-based permissions
  - File sharing and management system

### 3. Mobile SDK
- Mobile applications (iOS/Android)
- Native performance with optimized battery usage
- Main modules:
  - Push notifications with rich media support
  - Mobile chat interface supporting all messaging channels (WhatsApp, TikTok, Facebook, Instagram, Telegram, Viber, LINE, WeChat, SMS, Email, Live Chat)
  - Offline message support with automatic sync when online
  - Background message processing
  - Location sharing and media attachments

## Implementation Roadmap
1. Documentation analysis (completed)
2. SDK architecture design
3. Backend SDK development first
4. Parallel Web and Mobile SDK development
5. Integration and testing
6. Beta release
7. Feedback collection and refinement